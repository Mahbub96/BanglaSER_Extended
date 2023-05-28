# banglaSER

## Description

This repository contains the Bangla Speech Emotion Recognition (banglaSER_ext) dataset. The dataset consists of Bangla voice samples categorized according to the following identifiers:

<style>
table {
  width: 100%;
  border-collapse: collapse;
  text-align: left;
}

table th, table td {
  padding: 8px;
  border: 1px solid #ddd;
}

table th {
  background-color: #f2f2f2;
  font-weight: bold;
}

table tr:nth-child(even) {
  background-color: #f9f9f9;
}

table tr:hover {
  background-color: #f5f5f5;
}
</style>

<table>
  <tr>
    <th>Identifier</th>
    <th>Meaning</th>
  </tr>
  <tr>
    <td>Mode</td>
    <td><code>03</code> (Audio-only)</td>
  </tr>
  <tr>
    <td>Statement Type</td>
    <td><code>01</code> (Scripted)</td>
  </tr>
  <tr>
    <td>Emotion</td>
    <td>
      <code>01</code> (Happy), <code>02</code> (Sad), <code>03</code> (Angry), <code>04</code> (Surprised), <code>05</code> (Neutral), <code>06</code> (Disgust), <code>07</code> (Fear)
    </td>
  </tr>
  <tr>
    <td>Intensity</td>
    <td><code>01</code> (Mild), <code>02</code> (Normal), <code>03</code> (Strong)</td>
  </tr>
  <tr>
    <td>Statement</td>
    <td>
      Corresponding Bangla statements with their English translations:<br>
      <code>01</code> - "Barota beje geche" (English: It's twelve o'clock)<br>
      <code>02</code> - "Ami agei jantam amonta hobe" (English: I knew something like this would happen.)<br>
      <code>03</code> - "e kemon upohar?" (English: What kind of gift is this?)<br>
      <code>04</code> - "Rastay etto jam" (English: The road is so jammed)<br>
      <code>05</code> - "Baghta edikei tere asche" (English: The tiger is coming here)
    </td>
  </tr>
  <tr>
    <td>Repetition</td>
    <td><code>01</code> (1st repetition), <code>02</code> (2nd repetition), <code>03</code> (3rd repetition)</td>
  </tr>
  <tr>
    <td>Actor</td>
    <td>
      <code>01</code> (First actor), <code>02</code> (Second actor), ..., <code>50</code> (Fifty actor) - Odd numbers
