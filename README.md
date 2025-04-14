# Kubernetes-Cluster-
<head>
    <title>Learning Kubernetes with Minikube</title>
</head>
<body>
    <header>
        <h1>Learning Kubernetes with Minikube</h1>
    </header>

    <section>
        <h2>Objective</h2>
        <p>
            The objective of this project is to learn how to deploy and manage applications
            in Kubernetes locally using Minikube.
        </p>
    </section>

    <section>
        <h2>Tools Used</h2>
        <ul>
            <li><strong>Minikube:</strong> A tool for running Kubernetes clusters locally.</li>
            <li><strong>kubectl:</strong> Kubernetes command-line tool to interact with the cluster.</li>
            <li><strong>Docker:</strong> Used for containerizing applications.</li>
        </ul>
    </section>

    <section>
        <h2>Steps to Set Up the Cluster</h2>
        <ol>
            <li><strong>Start Minikube Cluster:</strong> 
                <p>Use the command <code>minikube start</code> to set up a local Kubernetes cluster.</p>
            </li>
            <li><strong>Create Deployment:</strong>
                <p>Create a <code>deployment.yaml</code> file to define the deployment of the application.</p>
            </li>
            <li><strong>Expose the Application:</strong>
                <p>Use a <code>service.yaml</code> file to expose the app to external access.</p>
            </li>
            <li><strong>Verify Pods and Services:</strong>
                <p>Check the pods and services using the <code>kubectl get pods</code> and <code>kubectl get svc</code> commands.</p>
            </li>
            <li><strong>Scale the Deployment:</strong>
                <p>Use the <code>kubectl scale</code> command to scale the deployment up or down.</p>
            </li>
            <li><strong>View Logs:</strong>
                <p>Use the <code>kubectl describe pod</code> command to view the logs of the pods.</p>
            </li>
        </ol>
    </section>

    <section>
        <h2>Conclusion</h2>
        <p>
            This project provides hands-on experience with setting up a Kubernetes cluster locally,
            deploying applications, managing services, and scaling deployments. It is a valuable
            resource for anyone wanting to learn Kubernetes fundamentals.
        </p>
    </section>

    <footer>
        <p>Learn Kubernetes, Manage Containers, and Explore DevOps!</p>
    </footer>
</body>
</html>
