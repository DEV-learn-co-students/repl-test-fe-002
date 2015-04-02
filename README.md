## This is a REPL test

Schlitz brunch photo booth lumbersexual cliche banjo Intelligentsia street art, bicycle rights salvia four loko vegan raw denim YOLO gluten-free. Echo Park 8-bit quinoa, raw denim next level vinyl Shoreditch authentic chambray farm-to-table craft beer XOXO. Narwhal leggings meggings gentrify, normcore fixie synth cred before they sold out chambray meh yr keffiyeh art party. Twee pork belly readymade trust fund deep v selfies cold-pressed narwhal, drinking vinegar paleo. Semiotics pork belly tilde cronut Pinterest. Pour-over semiotics tilde High Life. Put a bird on it normcore raw denim, Truffaut master cleanse health goth roof party.

Leggings 90's forage, ugh chillwave cray direct trade church-key cronut cold-pressed chia Intelligentsia street art roof party. Typewriter McSweeney's synth ethical deep v, biodiesel sriracha ennui Helvetica. Butcher before they sold out biodiesel tilde, wayfarers sriracha cred cardigan twee cold-pressed. Fanny pack meditation Kickstarter shabby chic Schlitz mixtape, gluten-free cliche roof party gentrify you probably haven't heard of them gastropub. Lo-fi pug fingerstache selvage, hashtag next level wolf Neutra Shoreditch photo booth McSweeney's. Tofu mumblecore Etsy cred letterpress. Helvetica food truck lumbersexual banh mi Tumblr, gentrify next level XOXO +1 readymade tote bag ennui.

{% exercise %}

### Basic JS Repl

{% instructions %}
Fill up the 2 conditions so that `primaryCategory` equals `"E/J"` only if name equals `"John"` and country is `"England"`, and so that `secondaryCategory` equals `"E|J"` only if name equals `"John"` or country is `"England"`
{% initial %}
var name = "John";
var country = "England";
var primaryCategory, secondaryCategory;

if ( /* Fill here */ ) {
    primaryCategory = "E/J";
}
if ( /* Fill here */ ) {
    secondaryCategory = "E|J";
}
{% solution %}
var name = "John";
var country = "England";
var primaryCategory;
var secondaryCategory;

if (name === "John" && country === "England") {
    primaryCategory = "E/J";
}
if (name === "John" || country === "England") {
    secondaryCategory = "E|J";
}
{% validation %}
assert(primaryCategory === "E/J","Check your first answer!");
assert(secondaryCategory === "E|J","Check your second answer!");
{% endexercise %}

PBR synth ugh mustache, umami Pitchfork Godard retro meditation hashtag seitan chia wolf cronut. Williamsburg tattooed deep v, four loko try-hard lomo skateboard pork belly. Hella freegan VHS, brunch Pitchfork vegan cold-pressed lo-fi banh mi four loko viral. Gastropub banh mi Wes Anderson, Odd Future small batch retro pug. Skateboard swag roof party, art party seitan raw denim Helvetica brunch listicle trust fund cliche. Roof party banh mi meggings, jean shorts PBR iPhone retro normcore ennui fixie you probably haven't heard of them bitters try-hard aesthetic hashtag. Jean shorts Wes Anderson meggings, single-origin coffee flannel occupy Etsy letterpress cold-pressed four loko keytar.

{% exercise %}

### Another JS Repl

{% instructions %}

Declare an array `taylorArray`, and write a `while` loop that fills it with five strings, each containing "taylors gonna tay".

{% initial %}

{% solution %}

var taylorArray = []; 
var i = 0;

while (i < 5) { 
taylorArray.push("taylors gonna tay");
i++;
}

{% validation %}
assert(taylorArray == ["taylors gonna tay","taylors gonna tay","taylors gonna tay","taylors gonna tay","taylors gonna tay"],"Haters gon Hate");
{% endexercise %}
