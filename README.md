# robosys
学校の課題です。

<動作>

echo 1 > /dev/myled0　で5回点滅する。

echo 2 > /dev/myled0　で短く30回点滅する。

echo 3 > /dev/myled0　で長く3回点滅する。



<使い方>

1.make

2.$sudo insmod myled.ko

3.$sudo chmod 666 /dev/myled0
