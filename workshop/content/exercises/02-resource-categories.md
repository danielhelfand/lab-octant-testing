The overview page for a namespace will show all namespaced resources for a namespace. This can be a lot of information.

If you are only interested in specific resource types, you can instead click on the resource type in the left hand side menu.

![Resource Categories](octant-resource-categories.png)

Click on the **Overview->Workloads->Pods** category. This will bring up a list of just the pods running in the namespace.

![Pods Category](octant-pods-category.png)

You can then select a specific pod to see the details page for it.

In this workshop environment, Octant has been set up such that only namespaced resources can be viewed. When you run Octant yourself, provided you have the appropriate roles, you will also be able to view cluster scoped resources in categories under **Cluster Overview** as well.
