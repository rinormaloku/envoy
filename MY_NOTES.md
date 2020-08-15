
# Setting up a fast build (slow)
./ci/run_envoy_docker.sh './ci/do_ci.sh bazel.dev'

# Setting up container (fast)
ci/docker_ci.sh