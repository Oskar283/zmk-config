
## local builds
First source the .venv
`source ~/zmk/.venv/bin/activate`

For local builds, the content inside build.yaml doesnt matter
Build command I use for local build WIP.
`west build --pristine -b nice_nano_v2 -s /home/oskar/zmk/app/  -- -DSHIELD=lily58_left -DZMK_CONFIG="/home/oskar/repo/zmk-config/config"`
output is then at `~/zmk/app/build/zephyr`
