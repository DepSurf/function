# Function: <code>evdev_detach_client</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void evdev_detach_client(struct evdev *evdev, struct evdev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff8166cef0)
Location: drivers/input/evdev.c:410
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
**Symbols:**

```
ffffffff8166cef0-ffffffff8166cf42: evdev_detach_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void evdev_detach_client(struct evdev *evdev, struct evdev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff816cd230)
Location: drivers/input/evdev.c:410
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
**Symbols:**

```
ffffffff816cd230-ffffffff816cd282: evdev_detach_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void evdev_detach_client(struct evdev *evdev, struct evdev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff816fb1d0)
Location: drivers/input/evdev.c:410
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
**Symbols:**

```
ffffffff816fb1d0-ffffffff816fb222: evdev_detach_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void evdev_detach_client(struct evdev *evdev, struct evdev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81710bb0)
Location: drivers/input/evdev.c:410
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
**Symbols:**

```
ffffffff81710bb0-ffffffff81710c02: evdev_detach_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void evdev_detach_client(struct evdev *evdev, struct evdev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (ffffffff81781e30)
Location: drivers/input/evdev.c:410
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
**Symbols:**

```
ffffffff81781e30-ffffffff81781e82: evdev_detach_client (STB_LOCAL)
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
In drivers/input/evdev.c (ffffffff817c393f)
Location: drivers/input/evdev.c:416
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff817eafaf)
Location: drivers/input/evdev.c:416
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff8182bb22)
Location: drivers/input/evdev.c:413
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff8185d496)
Location: drivers/input/evdev.c:394
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff81931662)
Location: drivers/input/evdev.c:381
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff8193890c)
Location: drivers/input/evdev.c:380
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff8191c17b)
Location: drivers/input/evdev.c:380
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff819be86e)
Location: drivers/input/evdev.c:380
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff81b1d6bc)
Location: drivers/input/evdev.c:380
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff81caf69c)
Location: drivers/input/evdev.c:380
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff81d16c9c)
Location: drivers/input/evdev.c:380
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff81dcc94c)
Location: drivers/input/evdev.c:380
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffff800010a9e324)
Location: drivers/input/evdev.c:394
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void evdev_detach_client(struct evdev *evdev, struct evdev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (c0b7e77c)
Location: drivers/input/evdev.c:394
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
**Symbols:**

```
c0b7e77c-c0b7e7d4: evdev_detach_client (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void evdev_detach_client(struct evdev *evdev, struct evdev_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/evdev.c (c000000000b7dd50)
Location: drivers/input/evdev.c:394
Inline: False
Direct callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
```
**Symbols:**

```
c000000000b7dd50-c000000000b7de44: evdev_detach_client (STB_LOCAL)
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
In drivers/input/evdev.c (ffffffe0006adfec)
Location: drivers/input/evdev.c:394
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff818124a6)
Location: drivers/input/evdev.c:394
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff817d9be6)
Location: drivers/input/evdev.c:394
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff81851626)
Location: drivers/input/evdev.c:394
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
In drivers/input/evdev.c (ffffffff8186c444)
Location: drivers/input/evdev.c:394
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
  - drivers/input/evdev.c:evdev_release
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
