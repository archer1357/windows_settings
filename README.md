# windows settings

## fix wake on lan not working

* settings => "power and sleep" => "additional power settings" => "choose what the power buttons do" => uncheck "turn on fast startup"

* device manager => network adapters => right click network device => properties => power management => tick all (except "only allow a magic packet to wake the computer" ?)

## stop computer randomly waking

* device manager => network adapters => right click network device => properties => advanced => disable "wake on magic packet when ..." ?

* device manager => network adapters => right click network device => properties => advanced => disable "wake on pattern match"
