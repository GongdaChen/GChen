1.Put two path files "90degree.txt" and "ISO_double_lane_change22" at chrono/chrono-build/bin/data/vehicle/paths

2.Uncomment one of these two lines at line 80.
std::string path_file("paths/ISO_double_lane_change22.txt");

std::string path_file("paths/90degree.txt");

3.Compile the file.

4.Run that exe file named "demo_VEH_SteeringController.exe" at chrono/chorno-build/bin/Release until the vehicle finish the turn.

5.An output file named "state.txt" is generated at chrono/chorno-build/bin/Release/DEMO_OUTPUT/STEERING_CONTROLLER