# Starstream api

#### [JavaScript built-in objects](http://es5.github.io/multi.html#x15-toc)

#### [setTimeout(callback, ms)](http://nodejs.org/api/globals.html#globals_settimeout_cb_ms)

#### [setInterval(callback, ms)](http://nodejs.org/api/globals.html#globals_setinterval_cb_ms)

#### [nextTick(callback)](http://nodejs.org/api/process.html#process_process_nexttick_callback)

## screen
#### screen.write(string)
Write string to player terminal. Does not automatically append newlines.

## ship
#### ship.thrusters
Array of the ship's thrusters

## Class: Thruster
#### thruster.force([force])
Sets thruster force if specified, returns current force

    screen.write('Thruster force: ' + ship.thrusters[0].force(3));
    // Thruster force: 3
