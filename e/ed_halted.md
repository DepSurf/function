# Function: <code>ed_halted</code>

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
In drivers/usb/host/ohci-hcd.c (ffffffff8163f1ad)
Location: drivers/usb/host/ohci-q.c:831
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffff8169fd12)
Location: drivers/usb/host/ohci-q.c:832
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffff816cde62)
Location: drivers/usb/host/ohci-q.c:832
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffff816e2582)
Location: drivers/usb/host/ohci-q.c:832
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffff8174eda2)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffff8178f285)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffff817b5a65)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffff817f50f2)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffff81825f52)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ed_halted(struct ohci_hcd *ohci, struct td *td, int cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818f6780)
Location: drivers/usb/host/ohci-q.c:833
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
```
**Symbols:**

```
ffffffff818f6780-ffffffff818f68b8: ed_halted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ed_halted(struct ohci_hcd *ohci, struct td *td, int cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818ff2d0)
Location: drivers/usb/host/ohci-q.c:833
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
```
**Symbols:**

```
ffffffff818ff2d0-ffffffff818ff408: ed_halted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ed_halted(struct ohci_hcd *ohci, struct td *td, int cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818e2a30)
Location: drivers/usb/host/ohci-q.c:833
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
```
**Symbols:**

```
ffffffff818e2a30-ffffffff818e2b68: ed_halted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ed_halted(struct ohci_hcd *ohci, struct td *td, int cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8197eb40)
Location: drivers/usb/host/ohci-q.c:833
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
```
**Symbols:**

```
ffffffff8197eb40-ffffffff8197ec97: ed_halted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ed_halted(struct ohci_hcd *ohci, struct td *td, int cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81ada2b0)
Location: drivers/usb/host/ohci-q.c:833
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
```
**Symbols:**

```
ffffffff81ada2b0-ffffffff81ada459: ed_halted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ed_halted(struct ohci_hcd *ohci, struct td *td, int cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81c65490)
Location: drivers/usb/host/ohci-q.c:833
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
```
**Symbols:**

```
ffffffff81c65490-ffffffff81c65639: ed_halted (STB_LOCAL)
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
In drivers/usb/host/ohci-hcd.c (ffffffff81cce234)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffff81d83134)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffff800010a601d8)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (c0b32c68)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (c000000000b2e5a0)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffe00067b64a)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffff817de332)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8181add2)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
In drivers/usb/host/ohci-hcd.c (ffffffff81834f22)
Location: drivers/usb/host/ohci-q.c:833
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
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
</ul>
