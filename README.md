# audio-arabic-review
<table>
  <tr>
    <th>Model Name</th>
    <th>Small Text</th>
    <th>Small Text with English Terms</th>
    <th>Large Text</th>
    <th>Large Text with English Terms</th>
    <th>Text with Tashkeel (تشكيل)</th>
    <th>Text without Tashkeel</th>
    <th>Upvote Score</th>
  </tr>
  <tr>
    <td>Model A</td>
    <td><audio controls><source src="audio-link-a-small.mp3" type="audio/mpeg"></audio></td>
    <td><audio controls><source src="audio-link-a-small-eng.mp3" type="audio/mpeg"></audio></td>
    <td><audio controls><source src="audio-link-a-large.mp3" type="audio/mpeg"></audio></td>
    <td><audio controls><source src="audio-link-a-large-eng.mp3" type="audio/mpeg"></audio></td>
    <td><audio controls><source src="audio-link-a-tashkeel.mp3" type="audio/mpeg"></audio></td>
    <td><audio controls><source src="audio-link-a-no-tashkeel.mp3" type="audio/mpeg"></audio></td>
    <td>
      <span id="score-a">0</span>
      <button onclick="upvote('score-a')">Upvote</button>
    </td>
  </tr>
  <!-- Add more rows for other models here -->
</table>

<script>
  function upvote(id) {
    var score = document.getElementById(id);
    var currentScore = parseInt(score.innerText);
    score.innerText = currentScore + 1;
  }
</script>