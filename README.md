## Readme

### Clone repository 
`$ git clone https://github.com/akajains/longest_increasing_continuous_subsequence.git`

`$ cd longest_increasing_continuous_subsequence`

### Build Docker Image
`$ docker-compose build`

### Run service
`$ docker-compose up`

### Run application with argument (Example:)
`$ docker run -w /app/src pythonseqfinder python script.py "1 2 4 3 6 8 9 23"`

`3 6 8 9 23`
### Run Test
`$ docker-compose run test`

#### Example
![image](https://user-images.githubusercontent.com/7066357/118386516-4de40380-b65b-11eb-909c-a0e9ed42db54.png)

- No Host depencdency
- Small size - Container based on Alpine distro
- Integrated with Github Actions
- Continuous Integration: Linting & Unit testing
