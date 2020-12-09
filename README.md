# helm-jellyfin-simple

I wanted a simple chart for deploying jellyfin, not one that had an abundance of options that made no sense for deploying it to a single node, and I specifically wanted to test function side-by-side with an emby server without them conflicting.

## Usage

Modify the values.yaml to match your servers environment, ensure the paths defined actually exist on the host and have sufficient space, ensure kubernetes is installed and you can access it, and it's the correct environment, and then simply run:

    helm install -f values.yaml jellyfin ./

Adjust the values.yaml and ./ to the path to the helm chart if not run from inside.

