<template>
    <h2>요약</h2>
    <div class="firstBox">
      <dl>
        <dt>10dB</dt>
        <dd>평균 소음</dd>
        <dd>지난 1시간 동안</dd>
      </dl>
      <dl>
        <dt>10개</dt>
        <dd>주의</dd>
        <dd>지난 1시간 동안</dd>
      </dl>
      <dl>
        <dt>3개</dt>
        <dd>경고</dd>
        <dd>지난 1시간 동안</dd>
      </dl>
      <dl>
        <dt>10dB</dt>
        <dd>평균 소음</dd> 
        <dd>지난 1시간 동안</dd>
      </dl>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HelloWorld'
  }
  </script>
  
  <style scoped>
  h2 {
    margin: 2% 0 0 5%;
    font-size: 25px;
  }
  
  .firstBox {
    width: 800px;
    height: 160px;
    margin: 1% 0 0 5%;
    background: #FFFFFF;
    box-shadow: 2px 2px 3px rgba(0, 0, 0, 0.16);
  }
  
  .firstBox dl {
    width: 200px;
    height: 100px;
    float: left;
    text-align: left;
    margin-top: 20px;
  }
  
  .firstBox dl dt,
  .firstBox dl dd {
    margin-left: 50px;
  }
  
  .firstBox dl dt {
    margin-top: 20px;
    margin-bottom: 12px;
    font-size: 30px;
    font-weight: bold;
  }
  
  .firstBox dl dd:first-of-type {
    font-size: 20px;
    font-weight: bold;
    margin-bottom: 8px;
  }
  
  .firstBox dl dd:nth-of-type(2) {
    font-size: 15px;
  }
  </style>
  