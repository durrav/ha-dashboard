# ha-dashboard

Hi and welcome to my Home Assistant Github page.<br>
Here I will be sharing code for my dashboard cards, template sensors and other fun stuff.

My dashboard is mainly built on <a href="https://github.com/piitaya/lovelace-mushroom">Mushroom cards</a>, so you will need to install that to use the cards.<br>
You will also need <a href="https://github.com/ofekashery/vertical-stack-in-card">Vertical Stack-in card</a> and <a href="https://github.com/thomasloven/lovelace-card-mod">Card-mod</a>.

<h2>Lovelace cards:</h2><br>

- Greeting card
- Lock card
- Room card
- Vacuum card
- Markdown card: What's for dinner (combine with input_text helpers and a normal entities card)


Greeting card:<br>
![image](https://github.com/durrav/ha-dashboard/assets/58232568/1d632b4e-056e-4143-b259-9a0e04bf6bfa)

Lock card:<br>
![image](https://github.com/durrav/ha-dashboard/assets/58232568/7f6a26e1-4a55-4afb-9581-7ef7172ebdb4)

Room card:<br>
![image](https://github.com/durrav/ha-dashboard/assets/58232568/f034c55e-8f00-41c4-9556-3d66ebba3e58)

Vacuuum card:<br>
![image](https://github.com/durrav/ha-dashboard/assets/58232568/75ed1463-f2a4-4251-abbc-8cf545c7a50d)

What's for dinner markdown card:<br>
![image](https://github.com/durrav/ha-dashboard/assets/58232568/07bec645-a724-4d8e-899f-7887130d04b3)

Combine the above markdown card with a normal entities card and put one input_text helper for each day:<br>
![image](https://github.com/durrav/ha-dashboard/assets/58232568/8920d253-819e-4227-b356-1462984a3ae9)


<br>

<h2>Template sensors:</h2><br>

- Count active lights
- Count active media_players
- Greeting (to be used with Greeting card above)


The count active lights and media_players sensors can be used in a mushroom chip-card:<br>
![image](https://github.com/durrav/ha-dashboard/assets/58232568/b392c4bb-43ed-48be-8673-c8f7cddbf5fc)
