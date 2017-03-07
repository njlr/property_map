include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-property-map', 
  header_only = True,
  header_namespace = 'boost/property_map',
  exported_headers = subdir_glob([
    ('include/boost/property_map', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
