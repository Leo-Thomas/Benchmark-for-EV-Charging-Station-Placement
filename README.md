# Multi-Objective Benchmark for Optimal Urban Electric Vehicle Charging Station Placement

<!-- ABOUT THE PROJECT -->
## About the project

At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.

### Paper

Soon

<!-- GETTING STARTED -->
## Installation

pip install git+https://github.com/Leo-Thomas/Benchmark-for-EV-Charging-Station-Placement

## Data set description

The dataset includes 20 predictor variables, where each represents one station, and its value ranges from 0 to 4, indicating the encoded capacity level of that station. A value of 0 represents the lowest capacity, while a value of 4 represents the highest. Additionally, the dataset contains three target variables, which aim to optimize key performance indicators: travel time, the number of active stations, and the quality of service.

Our generation approach integrates MOEAs with a traffic simulation to determine the optimal values for our target variables, thereby identifying the most advantageous locations for charging stations. We selected the city of Cuenca, Ecuador, as the basis for our simulations and data acquisition. Cuenca serves as an exemplary model due to its unique urban layout, which combines historical areas with modern urban development, and its significant vehicular traffic and congestion. A resulting dataset of 2,000 unique entries, plus an additional testing subset of 414 entries, was generated.

The composition of both the original dataset and the isolated testing subset is as follows:

| Dataset    | Number of entries  | Description |
|----------|---------|--------------|
| Primary  | 2,000 | Full dataset for model training and analysis |
| Testing  | 414 | Independent subset for model testing |

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CITAITON -->
## Citation
```
Soon
```

<!-- CONTACT -->
## Contact

Rolando Armas - [ResearchGate](https://www.researchgate.net/profile/Rolando-Armas) - tarmas@yachaytech.edu.ec

Juan Pablo Astudillo - [LinkedIn](https://ca.linkedin.com/in/juan-pablo-astudillo-leon-ph-d-b9318151) - jastudillo@yachaytech.edu.ec

Leo Ramos - [LinkedIn](https://www.linkedin.com/in/leo-thomas-ramos/) - theleothomasramos@gmail.com

<br>
<br>


<p align="right">(<a href="#top">back to top</a>)</p>
