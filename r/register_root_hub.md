# Function: <code>register_root_hub</code>

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
In drivers/usb/core/hcd.c (ffffffff8160e0ce)
Location: drivers/usb/core/hcd.c:1081
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8166dcb8)
Location: drivers/usb/core/hcd.c:1072
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8169b998)
Location: drivers/usb/core/hcd.c:1073
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff816b0d87)
Location: drivers/usb/core/hcd.c:1077
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8171c3a2)
Location: drivers/usb/core/hcd.c:1066
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8175b0f4)
Location: drivers/usb/core/hcd.c:1068
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8177f624)
Location: drivers/usb/core/hcd.c:1068
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817bf528)
Location: drivers/usb/core/hcd.c:973
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817efe90)
Location: drivers/usb/core/hcd.c:973
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_root_hub(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bf1ec)
Location: drivers/usb/core/hcd.c:974
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff818bf1ec-ffffffff818bf3bc: register_root_hub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_root_hub(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1c819)
Location: drivers/usb/core/hcd.c:975
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81c1c819-ffffffff81c1c9e9: register_root_hub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_root_hub(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c0e5f5)
Location: drivers/usb/core/hcd.c:975
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81c0e5f5-ffffffff81c0e7c5: register_root_hub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_root_hub(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d15726)
Location: drivers/usb/core/hcd.c:982
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81d15726-ffffffff81d158f0: register_root_hub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_root_hub(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81ee026a)
Location: drivers/usb/core/hcd.c:982
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81ee026a-ffffffff81ee0438: register_root_hub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_root_hub(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1def0)
Location: drivers/usb/core/hcd.c:982
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81c1def0-ffffffff81c1e101: register_root_hub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_root_hub(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c84df0)
Location: drivers/usb/core/hcd.c:982
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81c84df0-ffffffff81c84ffc: register_root_hub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_root_hub(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d397f0)
Location: drivers/usb/core/hcd.c:957
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81d397f0-ffffffff81d399ff: register_root_hub (STB_LOCAL)
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
In drivers/usb/core/hcd.c (ffff800010a1de48)
Location: drivers/usb/core/hcd.c:973
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (c0af541c)
Location: drivers/usb/core/hcd.c:973
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (c000000000ad6e34)
Location: drivers/usb/core/hcd.c:973
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffe000641080)
Location: drivers/usb/core/hcd.c:973
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817a8270)
Location: drivers/usb/core/hcd.c:973
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff81799c89)
Location: drivers/usb/core/hcd.c:973
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817e4d10)
Location: drivers/usb/core/hcd.c:973
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817fef7c)
Location: drivers/usb/core/hcd.c:973
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
