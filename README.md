Collaboration with Kuzey Bektas

# C323p3mathgame
This project functions as a game to practice math.

## Functionality 
The following **required** functionality is completed:
* [] user sees two sets of buttons to select: one for difficulty (easy, medium, hard) and one for operation (+,-,x,/)
* [] user can select one of each category
* [] if user selects easy, only numbers 1-10 will be used to make the question
* [] if user selects medium, only numbers 1-25 will be used
* [] if user selectes hard, numbers less than 50 will be used
* [] only the operator the user selects will be used to generate math questions
* [] user can select number of questions using + or - for more, or less questions
* [] user presses 'start' to begin
* [] a new page with a math question is displayed
* [] user can input an answer and press done to get next question (or finish)
* [] a new question will be displayed, but won't show final grade until the end
* [] once all questions are answered, user presses 'done'
* [] user nativates to final page that displays their grade (correct / number of questions)
* [] user can press 'do it again' to navigate to first page and re-select new difficulty/operation

The folowing **extensions** are implemented:
* import android.os.Bundle
* import androidx.fragment.app.Fragment
* import android.view.LayoutInflater
* import android.view.View
* import android.view.ViewGroup
* import android.widget.Button
* import android.widget.TextView
* import androidx.navigation.findNavController
* import androidx.navigation.fragment.navArgs
  
## Video Walkthrough 

https://github.com/aublwill/C323p3mathgame/assets/143005409/bf1c9818-6b86-452d-84bd-4163d1720d42

## Notes
* For division questions, answer is rounded to whole number
* Numeric input won't allow negatives to be inserted (-)

## License
Copyright [2023] [Aubrey Williams]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
