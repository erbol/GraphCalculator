# GraphCalculator

Осталось непонимание относительно кода

            if !CGRectContainsPoint(bounds, origin) {
                
                let leftx = max(origin.x - bounds.maxX, 0)
                let rightx = max(bounds.minX - origin.x, 0)
                let downy = max(origin.y - bounds.minY, 0)
                let upy = max(bounds.maxY - origin.y, 0)
                startingHashmarkRadius = min(min(leftx, rightx), min(downy, upy)) / pointsPerHashmark + 1
                //println("startingHashmarkRadius = \(startingHashmarkRadius)")
            }
            
            Зачем он нужен ?
            min(min(leftx, rightx), min(downy, upy)) всегда равно нулю
            
