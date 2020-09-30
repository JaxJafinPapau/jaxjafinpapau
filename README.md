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

Veritone Translate is a React application that uses redux, sagas, and material-ui for use as a document translation tool. A user can upload any common document type such as .docx, .odt, .xlsx, .pdf, .txt, etc or enter free-form textual input to be translated to and from over 30 languages. I was given the app fresh out of prototyping from an offshore team and tasked with updating it for Veritone's new core back end, which runs the translation jobs.

![Translate Document Upload](/Translate_Doc_Upload.png)

![Translate Language Select](/Translate_Text_Upload_Language_Select.png)

![Translate History Tab](/Translate_History_Selected.png)

---

## Cool Stats

(provided by [anuraghazra](https://github.com/anuraghazra/github-readme-stats))

<img align="left" src="https://github-readme-stats.vercel.app/api?username=jaxjafinpapau&show_icons=true&theme=nord&count_private=true" />
<img align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jaxjafinpapau&layout=compact" />
