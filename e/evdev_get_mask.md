# Function: <code>evdev_get_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff8166e395)
Location: drivers/input/evdev.c:1021
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff816ce915)
Location: drivers/input/evdev.c:1021
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff816fc5e5)
Location: drivers/input/evdev.c:1021
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff817121ed)
Location: drivers/input/evdev.c:1021
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff8178341d)
Location: drivers/input/evdev.c:1021
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff817c483f)
Location: drivers/input/evdev.c:1027
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff817ebdcb)
Location: drivers/input/evdev.c:1026
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff8182c71b)
Location: drivers/input/evdev.c:1022
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff8185de3b)
Location: drivers/input/evdev.c:1000
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff81930947)
Location: drivers/input/evdev.c:991
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff81937eda)
Location: drivers/input/evdev.c:991
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff8191b752)
Location: drivers/input/evdev.c:991
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff819bdd3f)
Location: drivers/input/evdev.c:991
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff81b1dfb0)
Location: drivers/input/evdev.c:991
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int evdev_get_mask(struct evdev_client *client, unsigned int type, void *codes, u32 codes_size, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81caf860)
Location: drivers/input/evdev.c:991
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
**Symbols:**

```
ffffffff81caf860-ffffffff81caf9da: evdev_get_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int evdev_get_mask(struct evdev_client *client, unsigned int type, void *codes, u32 codes_size, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81d16e60)
Location: drivers/input/evdev.c:991
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
**Symbols:**

```
ffffffff81d16e60-ffffffff81d16fdb: evdev_get_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int evdev_get_mask(struct evdev_client *client, unsigned int type, void *codes, u32 codes_size, int compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81dccb10)
Location: drivers/input/evdev.c:991
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
**Symbols:**

```
ffffffff81dccb10-ffffffff81dccc8b: evdev_get_mask (STB_LOCAL)
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
In drivers/input/evdev.c (ffff800010a9fea0)
Location: drivers/input/evdev.c:1000
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (c0b802ac)
Location: drivers/input/evdev.c:1000
Inline: True
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
In drivers/input/evdev.c (c000000000b80110)
Location: drivers/input/evdev.c:1000
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffe0006ae826)
Location: drivers/input/evdev.c:1000
Inline: True
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
In drivers/input/evdev.c (ffffffff81812e4b)
Location: drivers/input/evdev.c:1000
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff817da58b)
Location: drivers/input/evdev.c:1000
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff81851fcb)
Location: drivers/input/evdev.c:1000
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
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
In drivers/input/evdev.c (ffffffff8186d14b)
Location: drivers/input/evdev.c:1000
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
