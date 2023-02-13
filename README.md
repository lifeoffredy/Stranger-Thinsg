# Stranger-Thinsg

use_bpm 124

3.times do :drum
  sample :bass_thick_c
  sleep 6
end

live_loop :bass do
  sample :bass_thick_c
  sleep 6
end

live_loop :stranger do
  sleep 0.25
  play :c4
  sleep 0.5
  play :e4
  sleep 0.5
  play :g3
  sleep 0.5
  play :b4
  sleep 0.5
  play :b4
  sleep 0.5
  play :g4
  sleep 0.5
  play :e4
  sleep 0.5
  play :c4
  sleep 0.5
end
