# Bàn – Gaussian splat AR

Static web page (PlayCanvas engine 2.23.3, WebXR) that shows `ban.sog` and lets you place it on the floor in AR.

- Desktop: drag to rotate, scroll / pinch to zoom.
- Android phone (Chrome + ARCore): tap "Xem bằng AR", sweep the floor, tap to place. Buttons rotate ±15°, slider scales 10–200 %.
- At 100 % the table is about 1.26 m tall. Change `BASE_SCALE` in `index.html` if the real size differs.
- WebXR only runs on HTTPS (or localhost). iPhone Safari does not support WebXR AR.

Splat: "huonganleak" by jsc – https://superspl.at/scene/a3864123 – CC BY 4.0
