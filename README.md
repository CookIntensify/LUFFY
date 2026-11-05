import os
workspace = "/workspace/dumps/workspace"
with open(os.path.join(workspace, "README.md")) as f:
    print(f.read())
