# react-book-web

<section>
  <h2>Add your Ticket</h2>
</section>

<script>
  var root = document.querySelector('section').createShadowRoot();
  root.innerHTML = '<style>h2{ color: red; }</style>' + '<h2>Hello World!</h2>';
</script>

## react

var sectionStyle = {
  color: 'red'
};
var AddTicket = React.createClass({
  render: function() {
    return (<section><h2 style={sectionStyle}>Hello World!</h2></section>)}
  })
ReactDOM.render(<AddTicket/>, mountNode);
