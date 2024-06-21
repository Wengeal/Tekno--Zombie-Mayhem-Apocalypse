# Mappen

* gamestate (enum)
* gamepanel (class)
* grid (package)

* model
    * Entity (interface)
        * getHP()
        * getPosition()
        * takeDamage(int damage)
        * moveX(int deltaX)
        * moveY(int deltaY)
        * remove()
    * PlayerEntities (interface)
        * shoot()
    * DamageGiving (interface)
        * attack(PlayerEntities)

    * drawableEntity (interface)
        * getPosition()
        * getSprite()

    * player
        * Move up/down
    * shot
        * calculate the row the shot is in.
        * Initialize shot with (speed), attack power, row, x-value, y-value.
    * enemies
        * spawn in random row
        * attack power, hp, have reached tower, have reached end of board
        * move right to left
    * towers
        * place in cell on board
        * shot
        * HP, attack power, row

    * board
        * Return num rows/cols
        * List containing shots/enemies
            * return whole list
            * return first in list
            * append to list
            * remove from list
        * Be able to add object(tower) to location on board
* view
    * player
    * towers
    * enemies
    * board
* controller
