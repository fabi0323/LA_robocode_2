# LA_robocode_2
```package MeyerFabian;
import robocode.JuniorRobot;

public class MeyerFabian extends JuniorRobot {
    public void run() {
        while (true) {
            ahead(100); 
            fire(1); 
        }
    }

    public void onHitWall() {
        turnLeft(90); 
    }

    public void onScannedRobot() {
        fire(2);
    }
}
```
