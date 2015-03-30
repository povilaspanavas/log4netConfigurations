# log4netConfigurations
I need to have similar configuration in different workplaces and projects and I want to have them ready for all the possible cases. So, I'll start putting them here.

Don't forget to call XmlConfigurator.Configure() or to put this in AssemblyInfo.cs file:
[assembly: log4net.Config.XmlConfigurator(Watch = true)]

You can create a logger in a class:
private static readonly ILog log = LogManager.GetLogger(typeof(MyApp));

