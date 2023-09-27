Collaboration with Kuzey Bektas

# C323p4mathgame
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
* [] toast is shown whether user answered question correctly ("Good job!") or not ("Wrong!") with corresponding sound
* [] a new question will be displayed, but won't show final grade until the end
* [] once all questions are answered, user presses 'done'
* [] user then navigates back to first page to play again
* [] user sees a message with their grade and whether they need to practice more or not (over/under 80%)

The folowing **extensions** are implemented:
* import android.graphics.Color
* import android.os.Bundle
* import androidx.fragment.app.Fragment
* import android.view.LayoutInflater
* import android.view.View
* import android.view.ViewGroup
* import android.widget.Button
* import android.widget.RadioButton
* import android.widget.TextView
* import android.media.MediaPlayer
* import android.widget.EditText
* import android.widget.Toast
* import androidx.navigation.findNavController
* import androidx.navigation.fragment.navArgs
  
## Video Walkthrough 

https://github.com/aublwill/C323.p3.mathgame/assets/143005409/e49d0cc0-9fb5-48df-b551-984dc83374af

## Notes
* For division questions, answer is rounded to whole number

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
