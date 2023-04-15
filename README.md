
<h1>The Pokemon App by : </h1>
<br/>
<h2>Elgbouri saad && Oukattou Soufiane<h2/>
<p>The Pokemon App is a mobile application designed for Android devices that allows users to view information about various Pokemon characters. The app features a user-friendly interface that enables users to search for Pokemon characters by name, view their detailed information, and filter them based on their type. It also includes a list of all Pokemon characters that can be scrolled through.</p>
<h2>Architecture</h2>
<p>The project is implemented using the Model-View-ViewModel (MVVM) architecture, which separates the presentation logic from the business logic. The project's main components are the following:</p>
<ul>
<li>Model: This layer contains the data-related classes, such as the Pokemon class, which holds the attributes of a Pokemon character, and the PokemonRepository class, which provides the data access layer for the application.</li>
<li>View: This layer is responsible for the application's user interface. It contains the activities, fragments, and adapters used to display the data and user interaction.</li>
<li>ViewModel: This layer acts as a bridge between the View and the Model layers. It contains the classes that hold the presentation logic, such as the PokemonListViewModel class, which retrieves the data from the repository and prepares it for the View layer.</li>
</ul>
<h2>API</h2>
<p>The app uses the RESTful API provided by PokeAPI to retrieve the data. The app's design is simple and intuitive.</p>
<h2>Features</h2>
<p>The app also allows users to view detailed information about a specific Pokemon character by clicking on its image in the list or search results. The Pokemon detail screen displays information such as the Pokemon's type, height, weight, and base stats.</p>
<h2>Technologies Used</h2>
<p>The technologies used to build this project are:</p>
<ul>
<li>Java programming language for the Android application development.</li>
<li>Android Studio as the Integrated Development Environment (IDE) for developing and testing the Android application.</li>
<li>Retrofit library for making API calls and handling HTTP requests and responses.</li>
<li>RecyclerView and CardView to display the data in a scrollable list and card format.</li>
<li>Material Components for creating UI elements and styles following the Material Design guidelines.</li>
</ul>
<h2>Retrofit</h2>
<p>We chose Retrofit because:</p>
<ul>
<li>Simplicity: Retrofit is easy to use and understand, with a simple interface that allows you to make HTTP requests and handle responses easily.</li>
<li>Type safety: Retrofit uses annotations to define the endpoints and request parameters, and generates the necessary code at compile time. This makes it type-safe and eliminates the need for manual parsing of responses.</li>
<li>Customization: Retrofit allows you to customize various aspects of the network requests, such as headers, query parameters, and timeouts, to suit your needs.</li>
</ul>
