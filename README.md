# Anonymous Video Demonstrations for ICLR Submission 1431

This repository provides anonymous video demonstrations supporting the experimental results in our submission.  
Videos cover **Meta-World long-horizon tasks**, **LIBERO-long**, and **Ravens extreme long-horizon benchmarks**.

All videos are self-contained and do not reveal any author identity.  
(For reviewers: videos load directly in the browser. No login required.)

---

## Summary Table of VLA Baseline Comparison

The following table summarizes the performance of OpenVLA, π₀, and our method on Meta-World, LIBERO-long and Ravens tasks.

| Method | MW – Pick-place | MW – Door-open | MW – Window-close | MW – coffee pull | MW – Hammer | LIBERO – long | Build a jenga tower | Construct a 4×4×3 pyramid | Build a House |
|--------|------------------|----------------|-------------------|------------------|--------------|----------------|-----------------------|----------------------------|----------------|
| **OpenVLA** | 0.95 | 0.9 | 1.0 | 0.95 | 0.85 | 0.65 | 0.0 | 0.0 | 0.0 |
| **π₀** | 0.9 | 1.0 | 1.0 | 0.9 | 0.9 | 0.6 | 0.0 | 0.0 | 0.0 |
| **LYRA (Ours)** | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 | 0.95 | 0.95 | 0.85 | 0.8 |

---

## Meta-World Long-Horizon Tasks (MW)

These videos demonstrate performance of our framework on the Meta-World benchmark, including pick-place, door open, window close, coffee pull, and hammer tasks.

| Task | Video |
|------|-------|
| MW – Pick-place | `mw-pick-place.mp4` |
| MW – Door-open | `mw-door-open.mp4` |
| MW – Window-close | `mw-window-close.mp4` |
| MW – Coffee-pull | `mw-coffee-pull.mp4` |
| MW – Hammer | `mw-hammer.mp4` |


<table>
<tr>
<td align="center">
<a href="mw-pick-place.mp4"><img src="imgs/mw-pick-place.jpg" width="220"/></a><br/>
MW – Pick-place
</td>
<td align="center">
<a href="mw-door-open.mp4"><img src="imgs/mw-door-open.jpg" width="220"/></a><br/>
MW – Door-open
</td>
<td align="center">
<a href="mw-window-close.mp4"><img src="imgs/mw-window-close.jpg" width="220"/></a><br/>
MW – Window-close
</td>
</tr>

<tr>
<td align="center">
<a href="mw-coffee-pull.mp4"><img src="imgs/mw-coffee-pull.jpg" width="220"/></a><br/>
MW – Coffee-pull
</td>
<td align="center">
<a href="mw-hammer.mp4"><img src="imgs/mw-hammer.jpg" width="220"/></a><br/>
MW – Hammer
</td>
</tr>
</table>

---

## LIBERO-long Tasks (10 long-horizon tasks)

We provide demonstrations of our framework for all 10 LIBERO-long tasks, most long-horizon tasks within LIBERO-long require only two primitives.

| Task ID | Video |
|---------|--------|
| LIBERO-long-task1 | `libero-long-task1.mp4` |
| LIBERO-long-task2 | `libero-long-task2.mp4` |
| LIBERO-long-task3 | `libero-long-task3.mp4` |
| LIBERO-long-task4 | `libero-long-task4.mp4` |
| LIBERO-long-task5 | `libero-long-task5.mp4` |
| LIBERO-long-task6 | `libero-long-task6.mp4` |
| LIBERO-long-task7 | `libero-long-task7.mp4` |
| LIBERO-long-task8 | `libero-long-task8.mp4` |
| LIBERO-long-task9 | `libero-long-task9.mp4` |
| LIBERO-long-task10 | `libero-long-task10.mp4` |

<table>
<tr>
<td align="center">
<a href="libero-task1.mp4"><img src="imgs/libero-task1.jpg" width="220"/></a><br/>
LIBERO-long Task 1
</td>
<td align="center">
<a href="libero-task2.mp4"><img src="imgs/libero-task2.jpg" width="220"/></a><br/>
LIBERO-long Task 2
</td>
<td align="center">
<a href="libero-task3.mp4"><img src="imgs/libero-task3.jpg" width="220"/></a><br/>
LIBERO-long Task 3
</td>
</tr>

<tr>
<td align="center">
<a href="libero-task4.mp4"><img src="imgs/libero-task4.jpg" width="220"/></a><br/>
Task 4
</td>
<td align="center">
<a href="libero-task5.mp4"><img src="imgs/libero-task5.jpg" width="220"/></a><br/>
Task 5
</td>
<td align="center">
<a href="libero-task6.mp4"><img src="imgs/libero-task6.jpg" width="220"/></a><br/>
Task 6
</td>
</tr>

<tr>
<td align="center">
<a href="libero-task7.mp4"><img src="imgs/libero-task7.jpg" width="220"/></a><br/>
Task 7
</td>
<td align="center">
<a href="libero-task8.mp4"><img src="imgs/libero-task8.jpg" width="220"/></a><br/>
Task 8
</td>
<td align="center">
<a href="libero-task9.mp4"><img src="imgs/libero-task9.jpg" width="220"/></a><br/>
Task 9
</td>
</tr>

<tr>
<td align="center">
<a href="libero-task10.mp4"><img src="imgs/libero-task10.jpg" width="220"/></a><br/>
Task 10
</td>
</tr>
</table>

---

## Ravens Extreme Long-Horizon Tasks

These tasks include extreme long step reasoning and assembly skills (require over 20 primitives), such as constructing a pyramid, building a house, or stacking a Jenga tower.

| Task | Video |
|------|--------|
| Ravens – Build a Jenga tower | `Ravens_jenga_tower.mp4` |
| Ravens – Build a 4×4×3 pyramid | `Ravens_pyramid-4x3.mp4` |
| Ravens – Build a house | `Ravens_build_house.mp4` |

<table>
<tr>
<td align="center">
<a href="Ravens_jenga_tower.mp4"><img src="imgs/Ravens_jenga_tower.jpg" width="240"/></a><br/>
Build a Jenga tower
</td>
<td align="center">
<a href="Ravens_pyramid-4x3.mp4"><img src="imgs/Ravens_pyramid-4x3.jpg" width="240"/></a><br/>
Construct a 4×4×3 pyramid
</td>
<td align="center">
<a href="Ravens_build_house.mp4"><img src="imgs/Ravens_build_house.jpg" width="240"/></a><br/>
Build a house
</td>
</tr>
</table>

---


