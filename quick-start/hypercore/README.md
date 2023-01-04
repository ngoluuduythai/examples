Hypercore:  is a secure, distributed append-only log.
1: Persistence
2: Many readers
  
  + gives each reader a reading capability (core.key)
  + discovery key (core.discoveryKey)
former is used to authorize the reader
rm -r reader-storage
rm -r writer-storage
node quick-start/hypercore/writer.mjs
hypercore key: 252d54a2cb4e42db1b32fecde18419d096e4dd2a87ce33050adc8ff6c028a3d9
node quick-start/hypercore/reader.mjs 252d54a2cb4e42db1b32fecde18419d096e4dd2a87ce33050adc8ff6c028a3d9
Skipping 0 earlier blocks...
Block 0: hh

Block 1: hhb