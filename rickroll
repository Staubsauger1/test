-- Rickroll Script for CC: Tweaked

-- Function to display text with a delay
local function typewrite(text, delay)
  for i = 1, #text do
    io.write(text:sub(i, i))
    os.sleep(delay)
  end
  print("")
end

-- URL of the Rickroll video
local url = "https://www.youtube.com/watch?v=dQw4w9WgXcQ"

-- Open the text on the screen
term.clear()
term.setCursorPos(1,1)
typewrite("Never Gonna Give You Up...", 0.05)
os.sleep(1)
typewrite("Playing the Rickroll video!", 0.05)
os.sleep(1)

-- Open the browser to the Rickroll video (requires an advanced computer)
if term.isColor() then
  shell.run("open", url)
else
  print("Please use an advanced computer to open URLs.")
end
