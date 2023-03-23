## Jeremy Bennett: Family Man, Fullstack Engineer, Musician, Outdoor Enthusiast

```ruby
class Api::V1::JeremyBennett < ApiBaseController
  def work
    profession = Developer.new(tools)
    render status: 200, json: FullStack.new(profession)
  end

  def music
    instruments = { decent: 'violin', learning: 'guitar' }
    render status: 206, json: Hobby.new(instruments)
  end

  def fun
    while free_time == true do
      activities = Fun.new(play)
    end
    render status: 418
  end
  
  def family
    super
  end

  private

    def tools
      params.require(:software_engineer).permit(
        :ruby,
        :rails,
        :elixir,
        :phoenix,
        :react,
        :docker
      )
    end

    def play
      params.require(:human).permit(:snow, :woods, :mountains, :get_outside)
    end
end

```

[![Linkedin: jeremy-bennett-jaxjafinpapau](https://img.shields.io/badge/visit%20my-LinkedIn-blue)](https://www.linkedin.com/in/jeremy-bennett-jaxjafinpapau/)
[![GitHub jaxjafinpapau](https://img.shields.io/github/followers/jaxjafinpapau?label=follow&style=social)](https://github.com/jaxjafinpapau )

## Professional Work

### Weedmaps.com
![Weedmaps Online Ordering](/wm_orders.png)

Weedmaps is the cannabis' industries leader in e-commerce and I contributed to order management and customer relationship management in Elixir/Phoenix, embedded storefronts in Typescript/Next.js/Node, and flagship weedmaps.com site in Ruby on Rails and Typescript/React. Most of my work with this team focused on facilitating online ordering to include piping and maintaining necessary user and payment data for analytics, establishing payment integrations with industry payment solutions providers, building self service tools to maintain customer product data, and limiting order amounts for jurisdictional compliance laws.

### RecruitMilitary
![RecruitMilitary Homepage](/rm_home.png)

RecruitMilitary is a job board and contingency recruiting firm that focuses on Veterans. I was a part of a small team that maintained of a mix of new and legacy Rails applications, challenged with containerization and dependency updates that contributed to the migration of applications from Linode to AWS and improved application security. My React contributions were mostly accessibility upgrades and improved automated accessibility scores from an average of 73% to 97%



### Veritone

#### Contact/RIPA

California requires that law enforcement agencies collect data about perceived race, gender, and sexual orientation when officers engage with the public and action is taken against them. I was paired with a senior front end engineer on my team to produce an application that could streamline the collection of data from officers and leverage cognitive analysis of the collected data to produce insights for law enforcement and civilian leadership.

The front end is a React application that uses redux with thunks for state management and server interaction, material-ui for component development, and jest for testing.

The back end of the application is a Ruby on Rails API that I was tasked with building from the ground up. It uses docker-compose to build an rspec-powered test environment with 100% test coverage. This back end also connects Contact to AiWare, Veritone's 'operating system for AI' to highlight PII for redaction and visualize the collected data with Veritone Illuminate.

![RIPA Form Flow](/RIPA.png)

#### Translate 
A React application that uses redux, sagas, and material-ui for use as a document translation tool. A user can upload any common document type such as .docx, .odt, .xlsx, .pdf, .txt, etc or enter free-form textual input to be translated to and from over 30 languages. I was given the app fresh out of prototyping from an offshore team and tasked with updating it for Veritone's new core back end. I also contribute to the machine learning powered translation engines which include a Python service for native document translations and a suite of Go engines for text translation.

![Translate History Tab](/Translate_History_Selected.png)

#### Identify

A React application with a focus on using facial recognition as an after-the-matter investigative tool. When a user uploads captured image or video content, they can run facial recognition matching the content against a library of images for potential matches and highlighting those above a particular confidence score.

![Identify Main Screen](/Identify.png)

### Engines

In addition to my team's front end application suite and Veritone-RIPA, I've had the rewarding opportunity to build and contribute to several back end services which at Veritone are packaged as engines. Engines are docker containers, and are frequently multi-staged builds leveraging a variety technologies such as Alpine base images and open source libraries. Some engines take advantage of 3rd party images or partner API services, while others are written in house to use open source machine learning algorithms such as Yolo for object detection and Tesseract for optical character recognition. Engines are orchestrated by a Go application which I have made contributions to as well.

## Cool Stats

(provided by [anuraghazra](https://github.com/anuraghazra/github-readme-stats))

<img align="left" src="https://github-readme-stats.vercel.app/api?username=jaxjafinpapau&show_icons=true&theme=nord&count_private=true" />
<img align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jaxjafinpapau&layout=compact" />
