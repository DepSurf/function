# Function: <code>urb_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8160ff20)
Location: drivers/usb/core/urb.c:14
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
```
**Symbols:**

```
ffffffff8160ff20-ffffffff8160ff47: urb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8166faf0)
Location: drivers/usb/core/urb.c:14
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffff8166faf0-ffffffff8166fb17: urb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8169d7c0)
Location: drivers/usb/core/urb.c:19
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffff8169d7c0-ffffffff8169d7e7: urb_destroy (STB_LOCAL)
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
In drivers/usb/core/urb.c (ffffffff816b2bc6)
Location: drivers/usb/core/urb.c:19
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_free_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8171e280)
Location: drivers/usb/core/urb.c:19
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffff8171e280-ffffffff8171e2a7: urb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8175cf80)
Location: drivers/usb/core/urb.c:19
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffff8175cf80-ffffffff8175cfb2: urb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817815b0)
Location: drivers/usb/core/urb.c:19
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffff817815b0-ffffffff817815e2: urb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817bfad0)
Location: drivers/usb/core/urb.c:19
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffff817bfad0-ffffffff817bfb05: urb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817f0450)
Location: drivers/usb/core/urb.c:19
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffff817f0450-ffffffff817f0485: urb_destroy (STB_LOCAL)
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
In drivers/usb/core/urb.c (ffffffff818c0572)
Location: drivers/usb/core/urb.c:19
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
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
In drivers/usb/core/urb.c (ffffffff818cbf48)
Location: drivers/usb/core/urb.c:19
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
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
In drivers/usb/core/urb.c (ffffffff818af568)
Location: drivers/usb/core/urb.c:19
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
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
In drivers/usb/core/urb.c (ffffffff819446b8)
Location: drivers/usb/core/urb.c:19
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_scuttle_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
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
In drivers/usb/core/urb.c (ffffffff81a9d16e)
Location: drivers/usb/core/urb.c:19
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
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
In drivers/usb/core/urb.c (ffffffff81c221fe)
Location: drivers/usb/core/urb.c:20
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
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
In drivers/usb/core/urb.c (ffffffff81c8916e)
Location: drivers/usb/core/urb.c:20
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
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
In drivers/usb/core/urb.c (ffffffff81d3dbbe)
Location: drivers/usb/core/urb.c:20
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
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
In drivers/usb/core/urb.c (ffff800010a2079c)
Location: drivers/usb/core/urb.c:19
Inline: True
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
In drivers/usb/core/urb.c (c0af7948)
Location: drivers/usb/core/urb.c:19
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
In drivers/usb/core/urb.c (c000000000ada1c0)
Location: drivers/usb/core/urb.c:19
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_free_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffe0006432d8)
Location: drivers/usb/core/urb.c:19
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffe0006432d8-ffffffe000643328: urb_destroy (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817a8830)
Location: drivers/usb/core/urb.c:19
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffff817a8830-ffffffff817a8865: urb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8179a240)
Location: drivers/usb/core/urb.c:19
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffff8179a240-ffffffff8179a275: urb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817e52d0)
Location: drivers/usb/core/urb.c:19
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffff817e52d0-ffffffff817e5305: urb_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void urb_destroy(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817ff530)
Location: drivers/usb/core/urb.c:19
Inline: False
Direct callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
**Symbols:**

```
ffffffff817ff530-ffffffff817ff565: urb_destroy (STB_LOCAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
