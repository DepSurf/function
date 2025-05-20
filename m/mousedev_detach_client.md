# Function: <code>mousedev_detach_client</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mousedev_detach_client(struct mousedev *mousedev, struct mousedev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff8166b6f0)
Location: drivers/input/mousedev.c:514
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_release
  - drivers/input/mousedev.c:mousedev_open
```
**Symbols:**

```
ffffffff8166b6f0-ffffffff8166b73f: mousedev_detach_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mousedev_detach_client(struct mousedev *mousedev, struct mousedev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff816cb9b0)
Location: drivers/input/mousedev.c:514
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
**Symbols:**

```
ffffffff816cb9b0-ffffffff816cb9ff: mousedev_detach_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mousedev_detach_client(struct mousedev *mousedev, struct mousedev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff816f9960)
Location: drivers/input/mousedev.c:514
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
**Symbols:**

```
ffffffff816f9960-ffffffff816f99af: mousedev_detach_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mousedev_detach_client(struct mousedev *mousedev, struct mousedev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff8170f4c0)
Location: drivers/input/mousedev.c:514
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
**Symbols:**

```
ffffffff8170f4c0-ffffffff8170f50f: mousedev_detach_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mousedev_detach_client(struct mousedev *mousedev, struct mousedev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff81780730)
Location: drivers/input/mousedev.c:514
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
**Symbols:**

```
ffffffff81780730-ffffffff8178077f: mousedev_detach_client (STB_LOCAL)
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
In drivers/input/mousedev.c (ffffffff817c273e)
Location: drivers/input/mousedev.c:514
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff817ea24e)
Location: drivers/input/mousedev.c:514
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff8182a841)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff8185c1d1)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff8192eaf1)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff81935e91)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff81919e51)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff819bc251)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff81b1bef8)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff81cadd38)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff81d15328)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff81dcaf77)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffff800010a9c684)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mousedev_detach_client(struct mousedev *mousedev, struct mousedev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (c0b7cee4)
Location: drivers/input/mousedev.c:511
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
**Symbols:**

```
c0b7cee4-c0b7cf3c: mousedev_detach_client (STB_LOCAL)
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
In drivers/input/mousedev.c (c000000000b7d570)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffe0006ace3e)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff818111e1)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff817d8921)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff81850361)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
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
In drivers/input/mousedev.c (ffffffff8186b07f)
Location: drivers/input/mousedev.c:511
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/mousedev.c:mousedev_release
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
