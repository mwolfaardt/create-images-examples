$unsplashUrl = "https://source.unsplash.com/random/1200x675/?city,night" 
## download image file
$fileName = "unsplash_random.jpg"
#twitter = 1200 x 675


#read rss feed
Write-Host "Downloading RSS Feed"
$feed = Invoke-RestMethod -Uri "https://www.cupofdev.com/index.xml" -UseBasicParsing -ContentType "application/xml"
$i=1
ForEach ($item in $feed) {
 #   Write-Host $item.title

Write-Host "Downloading Image"
Invoke-WebRequest -Uri $unsplashUrl -OutFile $fileName

## add text to the file using ImageMagick
## \n is linebreak
$text = $item.title
$posturl = $item.link
Write-Host "Generating image for $text ($posturl)"
#magick convert $fileName -background '#0008' -fill white -font 'Chiller' -gravity center -size 1024 -pointsize 100 caption:$text  -pointsize 20 caption:$posturl  +swap -gravity center -composite image_$i.jpg
magick convert $fileName -background '#0008' -fill white -gravity center -font 'Chiller' -size 1200x200 -pointsize 100 caption:$text -size 1200x40 -pointsize 20 caption:$posturl -append image_$i.jpg

$i++
}

