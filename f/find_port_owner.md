# Function: <code>find_port_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81603970)
Location: drivers/usb/core/hub.c:1899
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_claim_port
  - drivers/usb/core/hub.c:usb_hub_release_port
```
**Symbols:**

```
ffffffff81603970-ffffffff816039e8: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81663650)
Location: drivers/usb/core/hub.c:1896
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff81663650-ffffffff816636c8: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81691450)
Location: drivers/usb/core/hub.c:1815
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff81691450-ffffffff816914c8: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a69d0)
Location: drivers/usb/core/hub.c:1837
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff816a69d0-ffffffff816a6a42: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81711da0)
Location: drivers/usb/core/hub.c:1837
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff81711da0-ffffffff81711e12: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81750b10)
Location: drivers/usb/core/hub.c:1861
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff81750b10-ffffffff81750b84: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81774f70)
Location: drivers/usb/core/hub.c:1872
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff81774f70-ffffffff81774fe4: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b3090)
Location: drivers/usb/core/hub.c:1910
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff817b3090-ffffffff817b3104: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e37c0)
Location: drivers/usb/core/hub.c:1921
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff817e37c0-ffffffff817e3834: find_port_owner (STB_LOCAL)
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
In drivers/usb/core/hub.c (ffffffff818b2315)
Location: drivers/usb/core/hub.c:1928
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
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
In drivers/usb/core/hub.c (ffffffff818c0ca5)
Location: drivers/usb/core/hub.c:1928
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
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
In drivers/usb/core/hub.c (ffffffff818a3f95)
Location: drivers/usb/core/hub.c:1935
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
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
In drivers/usb/core/hub.c (ffffffff81938c05)
Location: drivers/usb/core/hub.c:1938
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
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
In drivers/usb/core/hub.c (ffffffff81a90545)
Location: drivers/usb/core/hub.c:1938
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
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
In drivers/usb/core/hub.c (ffffffff81c12465)
Location: drivers/usb/core/hub.c:1948
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
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
In drivers/usb/core/hub.c (ffffffff81c79295)
Location: drivers/usb/core/hub.c:1948
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
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
In drivers/usb/core/hub.c (ffffffff81d2f2f5)
Location: drivers/usb/core/hub.c:1976
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a11e18)
Location: drivers/usb/core/hub.c:1921
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffff800010a11e18-ffff800010a11eb0: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aea36c)
Location: drivers/usb/core/hub.c:1921
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
c0aea36c-c0aea3fc: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ac9180)
Location: drivers/usb/core/hub.c:1921
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
c000000000ac9180-c000000000ac9218: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe0006377c4)
Location: drivers/usb/core/hub.c:1921
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffe0006377c4-ffffffe000637838: find_port_owner (STB_LOCAL)
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
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179bba0)
Location: drivers/usb/core/hub.c:1921
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff8179bba0-ffffffff8179bc14: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178d830)
Location: drivers/usb/core/hub.c:1921
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff8178d830-ffffffff8178d8a4: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817d8640)
Location: drivers/usb/core/hub.c:1921
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff817d8640-ffffffff817d86b4: find_port_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int find_port_owner(struct usb_device *hdev, unsigned int port1, struct usb_dev_state ***ppowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f29b0)
Location: drivers/usb/core/hub.c:1921
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
```
**Symbols:**

```
ffffffff817f29b0-ffffffff817f2a24: find_port_owner (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
