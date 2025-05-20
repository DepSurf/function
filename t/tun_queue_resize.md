# Function: <code>tun_queue_resize</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tun_queue_resize(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816503c0)
Location: drivers/net/tun.c:2470
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
```
**Symbols:**

```
ffffffff816503c0-ffffffff816506bb: tun_queue_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tun_queue_resize(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816820a0)
Location: drivers/net/tun.c:2465
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
```
**Symbols:**

```
ffffffff816820a0-ffffffff81682399: tun_queue_resize (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff816974dd)
Location: drivers/net/tun.c:2535
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff8170237d)
Location: drivers/net/tun.c:3011
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff817410ae)
Location: drivers/net/tun.c:3425
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff8176519e)
Location: drivers/net/tun.c:3597
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff8179e658)
Location: drivers/net/tun.c:3602
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff817c20e8)
Location: drivers/net/tun.c:3606
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tun_queue_resize(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188bf10)
Location: drivers/net/tun.c:3574
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
```
**Symbols:**

```
ffffffff8188bf10-ffffffff8188c01b: tun_queue_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tun_queue_resize(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189a370)
Location: drivers/net/tun.c:3504
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_device_event
```
**Symbols:**

```
ffffffff8189a370-ffffffff8189a47b: tun_queue_resize (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8187cc1f)
Location: drivers/net/tun.c:3548
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff8190e1f7)
Location: drivers/net/tun.c:3560
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff81a62203)
Location: drivers/net/tun.c:3610
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff81bedbe3)
Location: drivers/net/tun.c:3623
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff81c46113)
Location: drivers/net/tun.c:3646
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff81cfba23)
Location: drivers/net/tun.c:3661
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffff8000109dc7dc)
Location: drivers/net/tun.c:3606
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (c0ac6dcc)
Location: drivers/net/tun.c:3606
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (c000000000a9ee80)
Location: drivers/net/tun.c:3606
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffe000627cc0)
Location: drivers/net/tun.c:3606
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff81786bb8)
Location: drivers/net/tun.c:3606
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff81766508)
Location: drivers/net/tun.c:3606
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff817b6f68)
Location: drivers/net/tun.c:3606
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
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
In drivers/net/tun.c (ffffffff817d11b8)
Location: drivers/net/tun.c:3606
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
