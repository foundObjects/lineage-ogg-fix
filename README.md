# LineageOS Ogg Vorbis Playback Fix
Quick and dirty hack to fix OGG Vorbis playpack on LineageOS for the OnePlus 5T (dumpling)

This works by REPLACING `/vendor/etc/audio_policy_configuration.xml` with a fixed version. 
Since that version was taken from a dumpling LineageOS, it might not work properly on any other device/setup.
