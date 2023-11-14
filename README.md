<h1 align="center">AirBNB Clone</h1>

```scss
@use 'base/variables' as v;
@use 'base/mixins' as m;

.barra {
    display: none;

    @include m.tablet {
        align-items: center;
        display: flex;
        justify-content: space-between;
    }

    &__navegacion {
        display: flex;
        gap: 4rem
    }

    &__link {
        color: v.$blanco;
    }

    &__nombre {
        color: v.$blanco;
        margin: 0;
    }
}
```

## About the project
<table width="100%">
    <tbody width="100%">
        <tr>
            <td rowspan=5 align="rigth">
                <img src="https://github.com/marcosguz/airbnb/assets/75583218/ea23f4d2-6181-4c1d-9401-dd299a5c294b" width="500px">
            </td>
        </tr>
        <tr>
            <td align="justify">This web application is developed for educational purposes to implement preprocessor code.</td>
        </tr>
        <tr>
            <td align="justify">
				<a href="https://air-bnb-site-app.netlify.app/">AirBNB</a>
			</td>
        </tr>
    </tbody>
</table>

## Developed with
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SASS Badge](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)

## How to contribute?
Contributions are what make the open source community an amazing place to learn, inspire, and create. Any contribution you make is greatly appreciated.

1. Fork the project.
2. Create a feature branch: (git checkout -b features/amazing-feature).
3. Commit your changes: (git commit -m 'Add an Amazing Feature').
4. Upload your changes to the branch: (features/amazing-feature)
5. Open a pull request

## License
Distributed under the MIT license. See the `LICENSE` file for more information.

## Contact
Marcos Guzmán

<a href="https://www.linkedin.com/in/marcos-guzman-nazareno" target="blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Marcos"/>
</a>
<a href="https://twitter.com/marccosgz" target="blank">
      <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
</a>

## Recognitions
- [Sass](https://github.com/sass/sass)
- [Marked](https://marked.js.org/)
