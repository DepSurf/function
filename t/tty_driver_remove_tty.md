# Function: <code>tty_driver_remove_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_remove_tty(struct tty_driver *driver, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e2f80)
Location: drivers/tty/tty_io.c:1444
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:release_tty
```
**Symbols:**

```
ffffffff814e2f80-ffffffff814e2fb1: tty_driver_remove_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8153236e)
Location: drivers/tty/tty_io.c:1449
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155eaa2)
Location: drivers/tty/tty_io.c:1449
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572097)
Location: drivers/tty/tty_io.c:1217
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d89ba)
Location: drivers/tty/tty_io.c:1229
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81610e1a)
Location: drivers/tty/tty_io.c:1247
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162deaa)
Location: drivers/tty/tty_io.c:1239
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81661a7a)
Location: drivers/tty/tty_io.c:1241
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816840cb)
Location: drivers/tty/tty_io.c:1241
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8173544b)
Location: drivers/tty/tty_io.c:1242
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817515fb)
Location: drivers/tty/tty_io.c:1322
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8173548b)
Location: drivers/tty/tty_io.c:1337
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b5e4b)
Location: drivers/tty/tty_io.c:1329
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f1e1b)
Location: drivers/tty/tty_io.c:1321
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a49d2b)
Location: drivers/tty/tty_io.c:1317
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a93ceb)
Location: drivers/tty/tty_io.c:1326
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae675b)
Location: drivers/tty/tty_io.c:1324
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084f3d4)
Location: drivers/tty/tty_io.c:1241
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095b6bc)
Location: drivers/tty/tty_io.c:1241
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008edd18)
Location: drivers/tty/tty_io.c:1241
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052d154)
Location: drivers/tty/tty_io.c:1241
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81649b4b)
Location: drivers/tty/tty_io.c:1241
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81629f9b)
Location: drivers/tty/tty_io.c:1241
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81677f0b)
Location: drivers/tty/tty_io.c:1241
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816930bb)
Location: drivers/tty/tty_io.c:1241
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
