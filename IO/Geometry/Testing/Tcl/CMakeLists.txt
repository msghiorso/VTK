if(VTK_DATA_ROOT)
  add_test_tcl(ParticleReader IO)
  add_test_tcl(Plot3DScalars IO)
  add_test_tcl(Plot3DVectors IO)
  add_test_tcl(TestAVSucdReader IO)
  add_test_tcl(TestChacoReader IO)
  add_test_tcl(TestGAMBITReader IO)
  add_test_tcl(TestPolygonWriters IO)
  add_test_tcl(TestSimplePointsReader IO)
  add_test_tcl(TestXYZMol IO)
  add_test_tcl(caffeine IO)
  add_test_tcl(motor Graphics)
  add_test_tcl(testHexaPenta Graphics)
endif()
