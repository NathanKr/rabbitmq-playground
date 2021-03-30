<h2>Motivation</h2>
Play with RabbitMQ which is the most popular open source message broker

<h2>Setup</h2>
<ul>
<li>install the server according to <a href='https://www.rabbitmq.com/download.html'>this</a></li>
<li>npm install amqplib -> for node clients</li>
</ul>


<h2>Points of interest</h2>
<ul>
<li>code is based on rabbitmq get started <a href='https://www.rabbitmq.com/getstarted.html'>here</a></li>
</ul>

<h2>Content</h2>
<table>
  <tr>
    <th>Directory</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>hello-world</td>
    <td>send.js is the producer app which send a message (text) to queue name hello. recv.js is the consumer app which read messages from the same queue</td>

  </tr>  
</table>
