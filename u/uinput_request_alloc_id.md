# Function: <code>uinput_request_alloc_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool uinput_request_alloc_id(struct uinput_device *udev, struct uinput_request *request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff816716f0)
Location: drivers/input/misc/uinput.c:62
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
**Symbols:**

```
ffffffff816716f0-ffffffff81671754: uinput_request_alloc_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool uinput_request_alloc_id(struct uinput_device *udev, struct uinput_request *request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff816d1bf0)
Location: drivers/input/misc/uinput.c:62
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
**Symbols:**

```
ffffffff816d1bf0-ffffffff816d1c54: uinput_request_alloc_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool uinput_request_alloc_id(struct uinput_device *udev, struct uinput_request *request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81701960)
Location: drivers/input/misc/uinput.c:62
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
**Symbols:**

```
ffffffff81701960-ffffffff817019c4: uinput_request_alloc_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool uinput_request_alloc_id(struct uinput_device *udev, struct uinput_request *request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81717190)
Location: drivers/input/misc/uinput.c:62
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
**Symbols:**

```
ffffffff81717190-ffffffff817171f6: uinput_request_alloc_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool uinput_request_alloc_id(struct uinput_device *udev, struct uinput_request *request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (ffffffff81788360)
Location: drivers/input/misc/uinput.c:100
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
**Symbols:**

```
ffffffff81788360-ffffffff817883c6: uinput_request_alloc_id (STB_LOCAL)
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
In drivers/input/misc/uinput.c (ffffffff817ca5d9)
Location: drivers/input/misc/uinput.c:103
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff817f1c99)
Location: drivers/input/misc/uinput.c:104
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff81831f47)
Location: drivers/input/misc/uinput.c:91
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff81863887)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff81937998)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff8193dd88)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff819216b8)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff819c452b)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff81b24838)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff81cb7cf8)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff81d1f478)
Location: drivers/input/misc/uinput.c:96
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff81dd51a8)
Location: drivers/input/misc/uinput.c:96
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffff800010aa4924)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool uinput_request_alloc_id(struct uinput_device *udev, struct uinput_request *request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/misc/uinput.c (c0b83454)
Location: drivers/input/misc/uinput.c:95
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
```
**Symbols:**

```
c0b83454-c0b834d0: uinput_request_alloc_id (STB_LOCAL)
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
In drivers/input/misc/uinput.c (c000000000b86b5c)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffe0006b2624)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff81816537)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff817ddc37)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff81857a17)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
In drivers/input/misc/uinput.c (ffffffff81872af9)
Location: drivers/input/misc/uinput.c:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
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
