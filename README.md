# Tutorial-Build-Script
Tutorial script lua


Hi, tutorial script in lua by Xsenskiy (GitHub)

sample:

function MENU()
mn == gg.choice({
	"Function 1",
	"Function 2",
	"Function 3",
},nil,"fast knife, etc standleo")
if mn == 1 then funtion1() end
if mn == 2 then funtion2() end
if mn == 1 then funtion3() end
end

function1()
//offset//
gg.clearList()
gg.toast("Function 1")
end

function2()
//offset//
gg.clearList()
gg.toast("Function 2")
end

function3()
//offset//
gg.clearList()
gg.toast("Function 3")
end

while true do
if gg.isVisible(true)then
MENUDM = 1
gg.setVisible(false)
end
if MENUDM == 1 then
MENU()
end
end



copy as a template if you don’t understand something

no sample:

function MENU()
mn == gg.choice({             =         Main menu(writing a function to have a menu or something like that) 


	"Function 1",
	"Function 2",
	"Function 3",                  =         Writing function
	
	
},nil,"fast knife, etc standleo")            =          description(not necessary)





if mn == 1 then funtion1() end
if mn == 2 then funtion2() end
if mn == 1 then funtion3() end
end                                                                          =  so that functions work without errors in "GameGuardian" 


function1()
//offset//
gg.clearList()
gg.toast("Function 1")                      =     a function that is not specified (offset is not specified, this is where "//offset//")
end

gg.searchNumber("4510805389554273485", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll("4510805391705112576", gg.TYPE_QWORD)
gg.processResume()
gg.clearList()
gg.toast("Fast Knife") - This is an offset and should be written like this:

function1()
gg.searchNumber("4510805389554273485", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll("4510805391705112576", gg.TYPE_QWORD)
gg.processResume()
gg.clearList()
gg.toast("тестируем")
gg.clearList()
gg.toast("Function 1")
end





Bye-Bye

Tutorial build script by Xsenskiy
