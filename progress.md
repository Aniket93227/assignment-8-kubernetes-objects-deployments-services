# Assignment 8 Progress

## Milestone 1: Repository Setup
- Created the GitHub repository.
- Cloned it to the local Devops folder.
- Added namespace, ConfigMap, Deployment, and Service manifests.
- Committed and pushed the initial files to GitHub.

## Milestone 2: Namespace and ConfigMap
- Created the devops-demo Namespace.
- Created the nginx-config ConfigMap.
- Verified the resources using kubectl.

## Milestone 3: Nginx Deployment and Service
- Deployed Nginx using a Kubernetes Deployment.
- Configured two replicas.
- Created a ClusterIP Service.
- Verified Deployment rollout, Pods, and Service.

## Milestone 4: Scaling
- Scaled the Nginx Deployment from two to three replicas.
- Verified that all three Pods became ready.
- Confirmed the Deployment replica count.

## Milestone 5: Rolling Update
- Updated the Nginx container image from nginx:1.26 to nginx:1.27.
- Applied the updated Deployment manifest.
- Verified rollout status and replica availability.