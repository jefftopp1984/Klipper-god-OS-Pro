This is a current PROGRESS snap shot of the KG-OS Pro system. It is NOT YET in release form but is simply a preview of the current progress. The next thing that will be finalized will be editing existing filament profiles, then adding/deleting filament profiles, and
finally getting it fully universal by adding a "setup wizard" that will ask the user a few questions about the physical hardware of their printer to allow certain macros to change their behavior as necessary.

Update 01-16-2026:

System is ready for transfer tests to other printers. Features include Filament Profile Create/Edit/Delete, Filament-Specific PID tunes with automatic updating, Abnormal Stop Recovery that works for any type of print interruption, Automatic layer timing with 3-stage layer time/speed control including a 2-stage printer throttle logic to reduce and restore velocity limit to adapt to real-time print conditions, Initialization Sequence that is fully guided and enforced, System has NO BLIND ERRORS meaning the user is informed of the corrective action and given a direct path to corrective action in the error message itself, More precise printer control to define flow rates and fan speeds that the slicer does not differentiate such as overhang flow vs bridge flow and solid infill flow and fan speed, Hardware-specific logic for system behavior, and System is 100% Interactive with no need to touch the configuration editor in Fluidd/Mainsail. Uploaded zip file with all files and logic needed.

Update 01-16-2026:

Fixed a minor bug in the filament profile change/delete and prohibited deletion of current profile to prevent a "ghost state" of the printer where a deleted profile is still in active memory. Will be continuing to test the system before final release.
