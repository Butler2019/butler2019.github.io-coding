#CODING

--packman model with Radish--
myShapes model=
  [
  roundedRect 100 100 5
  |> filled darkBlue
  |> scaleX 3
  |> scaleY 3
  ,
  wedge 10 0.75
  |> filled yellow
  |> move (0 , 40*sin(model.time))
  ,
  triangle 10
  |> filled hotPink
  |> rotate (degrees -90)
  |> move (-50,20)
  ,
  circle 10
  |> filled darkGreen
  |> move (-50,35)
  ,
  r|> filled darkGreen
  ,
  |> move (60,60)
  rect 10 100
  |> filled darkGreen
  |> rotate (degrees 90)
  |> move (-50,-60)
    ,
  rect 10 100
  |> filled darkGreen
  |> move (70,-60)
  ,
  rect 10 100
  |> filled darkGreen
  |> rotate (degrees 90)
  |> move (-60,5)
  ]
  

  
