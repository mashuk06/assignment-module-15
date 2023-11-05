<script setup>
    import Navbar from "@/Components/NavBar.vue"
</script>

<template>
    <Navbar></Navbar>
    <div class="container">
        <div class="accordion" id="accordionExample">
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingOne">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                        <h6>#2: Comparison of SSR and CSR: Write a brief essay (approximately 150-200 words) that
                            explains
                            the
                            differences between server-side rendering (SSR) and client-side rendering (CSR) in web
                            applications.
                            Discuss the advantages and disadvantages of each approach.</h6>
                    </button>
                </h2>
                <div id="collapseOne" class="accordion-collapse collapse" aria-labelledby="headingOne"
                    data-bs-parent="#accordionExample">
                    <div class="accordion-body">
                        <strong>Answer:</strong>
                        <p>Server-Side Rendering (SSR) and Client-Side Rendering (CSR) are two web rendering
                            approaches. SSR involves the server generating initial HTML content and sending it to the
                            client,
                            providing faster initial load times and better SEO. However, subsequent interactions may be
                            slower.
                            CSR sends minimal HTML and relies on the client's browser to render content using
                            JavaScript.
                            This
                            can lead to slower initial loads, but faster subsequent interactions and improved
                            interactivity.</p>
                        <br />

                        <p> Advantages of SSR include better SEO and faster initial loads, making it suitable for
                            content-driven
                            websites. However, it may require more server resources. CSR excels in interactivity and
                            responsiveness, making it ideal for dynamic web applications. It reduces server load for
                            subsequent
                            interactions, providing a smoother user experience. However, it may have slower initial load
                            times
                            and potentially poorer SEO performance.</p>
                        <br />

                        <p>The choice between SSR and CSR depends on the application's specific requirements. SSR is
                            favored
                            for content-heavy and SEO-sensitive sites, while CSR is ideal for highly interactive
                            applications.
                            Hybrid approaches like Server-Side Rendering with Client-Side Hydration (SSR + CSR) combine
                            the
                            benefits of both methods. This flexibility allows developers to choose the rendering
                            approach
                            that
                            best suits their project's needs.</p>
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingTwo">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                        <h6>#3: Inertia.js Features: List and explain the key features of Inertia.js, including its role
                            in
                            data-driven UI, client-side routing, and shared controllers. Provide practical examples to
                            illustrate these features.</h6>
                    </button>
                </h2>
                <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo"
                    data-bs-parent="#accordionExample">
                    <div class="accordion-body">
                        <strong>Answer:</strong>
                        <p>Inertia.js is a powerful JavaScript library that allows you to build
                            modern, reactive, and
                            dynamic web applications. Its key features include:</p>
                        <br />

                        <strong>1. Data-Driven UI:</strong>
                        <p>Inertia.js allows you to build data-driven UIs by sending server-side responses containing
                            both
                            the HTML and the data needed to render a page. This eliminates the need to write separate
                            API
                            endpoints and reduces boilerplate code.</p>

                        <br />

                        <strong>Example:</strong>
                        <p>Suppose you have a task management application. With Inertia.js, when a user navigates to
                            their
                            task
                            list, the server can send back the HTML for the task list page along with the data of the
                            tasks.
                            This way, the UI can be immediately populated with the tasks without needing an additional
                            API
                            call.</p>
                        <br />

                        <strong>2. Client-Side Routing:</strong>
                        <p>Inertia.js provides smooth client-side routing without the need for a dedicated router. This
                            allows for fast and seamless navigation within the application. It updates the URL and loads
                            content
                            dynamically without full page refreshes.</p>
                        <br />

                        <strong>Example:</strong>
                        <p>In a traditional multi-page application, clicking a link might result in a full page reload.
                            With
                            Inertia.js, when a user clicks on a link to view a specific task, it can be fetched and
                            rendered
                            on
                            the client side without reloading the entire page.</p>
                        <br />
                        <strong>3. Shared Controllers:</strong>
                        <p>Inertia.js supports shared controllers, which are classes or functions that can be used on
                            both
                            the server and the client. This promotes code reusability and helps maintain a consistent
                            application logic.</p>
                        <br />
                        <strong>Example:</strong>
                        <p>Let's say you have a form for adding new tasks. With shared controllers, you can define the
                            form
                            handling logic once and use it on both the server (for form submission) and the client (for
                            client-side validation before submission).</p>
                        <br />
                        <p>Inertia.js streamlines the development process by combining server-side rendering with
                            client-side
                            interactivity. It simplifies the flow of data between the server and the client, making it
                            an
                            excellent choice for building modern web applications.</p>
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingThree">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                        <h6>#5 Client-Side Components: Discuss the usage of a frontend framework Vue.js alongside
                            Inertia.js
                            to create client-side components. Explain how data is exchanged between the server and
                            client.
                        </h6>
                    </button>
                </h2>
                <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree"
                    data-bs-parent="#accordionExample">
                    <div class="accordion-body">
                        <strong>Answer:</strong>
                        <p>Using Vue.js alongside Inertia.js allows for the creation of dynamic and interactive
                            client-side components within a web application. Here's how they work together:</p>

                        <strong>1. Vue.js for Client-Side Components:</strong>
                        <p>Vue.js is a progressive JavaScript framework that facilitates the creation of interactive
                            user
                            interfaces. It allows you to build reusable components with encapsulated logic and state.
                            These
                            components can be seamlessly integrated into your web application.</p>
                        <br />
                        <strong>Example:</strong>
                        <p>Let's say you're building a task management application. You can use Vue.js to create
                            components
                            for
                            tasks, such as a task list, task details, and a form for adding new tasks.</p>
                        <br />
                        <strong>2. Inertia.js for Data Exchange:</strong>
                        <p>Inertia.js is a library that enables smooth integration of server-side and client-side
                            rendering.
                            It allows for seamless data exchange between the server and client without the need for
                            separate
                            API
                            endpoints.</p>
                        <br />
                        <strong>How Data is Exchanged:</strong>
                        <p>When a user interacts with the application, such as submitting a form or clicking a link,
                            Inertia.js
                            sends a request to the server. The server processes the request, potentially updating the
                            database,
                            and returns both the HTML and any necessary data back to the client. This data can then be
                            used
                            by
                            Vue.js to update the client-side components.</p>
                        <br />
                        <strong>Example:</strong>
                        <p>If a user adds a new task using a form created with Vue.js, Inertia.js can send the form data
                            to
                            the
                            server. The server processes the request, adds the task to the database, and returns the
                            updated
                            HTML along with any additional data. Vue.js can then use this data to update the task list
                            component
                            on the client side.</p>
                        <br />
                        <strong>3. Dynamic Updates with Vue.js:</strong>
                        <p>Vue.js excels at creating dynamic components that can react to changes in data. When
                            Inertia.js
                            updates the DOM with new HTML from the server, Vue.js can re-render the affected components
                            without
                            the need for a full page refresh. This provides a seamless and interactive user experience.
                        </p>
                        <br />
                        <strong>Example:</strong>
                        <p>After adding a new task, the server sends back updated HTML containing the newly added task.
                            Vue.js
                            can then update the task list component to include the new task without reloading the entire
                            page.</p>
                        <br />
                        <p>By combining Vue.js for client-side interactivity and Inertia.js for server-side rendering,
                            you
                            can
                            create a dynamic and responsive web application with efficient data exchange between the
                            server
                            and
                            client. This approach allows for a smoother user experience while still leveraging the
                            benefits
                            of
                            server-side rendering.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>

<style scoped>
</style>
