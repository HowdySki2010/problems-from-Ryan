let itemid = document.querySelectorAll(".container.itinerary .itinerary-item");
let message = document.createElement('div');
message.id = 'message';
let text = document.createElement('p')
let btn = document.createElement('a');
let space = document.createElement('p')
let cont = document.querySelector('#button-continue-shopping');
let link = 'https://dev.adventureres.com/responsive/index.php?resDate=12/9/2020&locationId=8&serviceGroupId=398&serviceId=839';
message.id = 'message';
text.innerHTML = "Hello! Looks like you're out for a full day. Would you like us to whip you up some lunch? ";
btn.className = 'button';
btn.innerText = 'Order Lunch';
btn.setAttribute('href', link);
for (let item of itemid) {
    if (item.getAttribute('id') === "item-990 group-982") {
        document.querySelector(".container.itinerary").insertBefore(message, cont)
        document.querySelector("#message").appendChild(text);
        document.querySelector("#message").appendChild(btn);
        document.querySelector("#message").appendChild(space);
    }
}
