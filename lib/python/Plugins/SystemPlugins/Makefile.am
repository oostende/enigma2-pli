installdir = $(pkglibdir)/python/Plugins/SystemPlugins

SUBDIRS = SoftwareManager PositionerSetup Satfinder \
	SkinSelector SatelliteEquipmentControl Videomode VideoTune Hotplug \
	DefaultServicesScanner DiseqcTester CommonInterfaceAssignment \
	CableScan FastScan OSDPositionSetup OSD3DSetup HdmiCEC \
	WirelessLan NetworkWizard

if HAVE_TEMPFANCONTROL
SUBDIRS += TempFanControl
endif

install_PYTHON =	\
	__init__.py
