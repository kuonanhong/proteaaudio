# 0.8.0
- fix: distinct data and playback handles
- introduce Sound handle type, an abstraction for playback audio track
- soundLoop, soundPlay return a Sound handle
- soundUpdate, soundStop take a Sound handle parameter

# 0.7.1.0
- add sampleFromMemoryPcm
- update stb_vorbis to v1.14

# 0.7.0.1
- better haddock

# 0.7.0
- use ByteString for in-memory sample loading
- fix: c++ mixer init caused segfaults sometimes
- use PulseAudio backend on Linux
