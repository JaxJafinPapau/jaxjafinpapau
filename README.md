## Jeremy Bennett: Family Man, Fullstack Engineer, Musician, Outdoor Enthusiast

```ruby
class Api::V1::JeremyBennett < ApiBaseController
  def work
    profession = Programmer.new(tools)
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

  private

    def tools
      params.permit(:react, :node, :rails, :python, :go, :docker)
    end

    def play
      params.permit(:snow, :woods, :mountains, :get_outside)
    end
end

```

[![Linkedin: jeremy-bennett-jaxjafinpapau](https://img.shields.io/badge/visit%20my-LinkedIn-blue)](https://www.linkedin.com/in/jeremy-bennett-jaxjafinpapau/)
[![GitHub jaxjafinpapau](https://img.shields.io/github/followers/jaxjafinpapau?label=follow&style=social)](https://github.com/jaxjafinpapau )


## Professional Work

### Veritone Translate 
A React application that uses redux, sagas, and material-ui for use as a document translation tool. A user can upload any common document type such as .docx, .odt, .xlsx, .pdf, .txt, etc or enter free-form textual input to be translated to and from over 30 languages. I was given the app fresh out of prototyping from an offshore team and tasked with updating it for Veritone's new core back end. I also contribute to the machine learning powered translation engines which include a Python service for native document translations and a suite of Go engines for text translation.

![Translate History Tab](/Translate_History_Selected.png)

### Veritone Identify

A React application with a focus on using facial recognition as an after-the-matter investigative tool. When a user uploads captured image or video content, they can run facial recognition matching the content against a library of images for potential matches and highlighting those above a particular confidence score.

![Identify Main Screen](/Identify.png)

### Back End Work

In addition to my team's front end application suite, I've had the rewarding opportunity to build and contribute to several back end services which at Veritone are packaged as engines. Engines are docker containers, and are frequently multi-staged builds leveraging a variety technologies such as Alpine base images and open source libraries. Some engines take advantage of 3rd party images or partner API services, while others are written in house to use open source machine learning algorithms such as Yolo for object detection and Tesseract for optical character recognition. Engines are orchestrated by a Go application which I have made contributions to as well.

![Bulk Tag Engine](/bulk_tag.png)
![Text Analytics Engine](/text_analytics.png)
![Native Doc Translation](/native_doc.png)

---

## Cool Stats

(provided by [anuraghazra](https://github.com/anuraghazra/github-readme-stats))

<img align="left" src="https://github-readme-stats.vercel.app/api?username=jaxjafinpapau&show_icons=true&theme=nord&count_private=true" />
<img align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jaxjafinpapau&layout=compact" />
