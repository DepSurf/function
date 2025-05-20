# Function: <code>uhci_free_td</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81644a50)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81644a50-ffffffff81644b10: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a5590)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff816a5590-ffffffff816a5656: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d3690)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff816d3690-ffffffff816d3756: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816e7d50)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff816e7d50-ffffffff816e7dff: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81754530)
Location: drivers/usb/host/uhci-q.c:125
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff81754530-ffffffff817545db: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81794b80)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff81794b80-ffffffff81794c2b: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817bb040)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff817bb040-ffffffff817bb0eb: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817fa970)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff817fa970-ffffffff817faa1a: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8182b7b0)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff8182b7b0-ffffffff8182b85a: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818fd880)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff818fd880-ffffffff818fd92a: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81906160)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff81906160-ffffffff8190620a: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818e9790)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff818e9790-ffffffff818e983a: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81985e30)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff81985e30-ffffffff81985eda: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae1ce0)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff81ae1ce0-ffffffff81ae1d9e: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6d6b0)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff81c6d6b0-ffffffff81c6d76e: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd4cc0)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff81cd4cc0-ffffffff81cd4d7e: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d89ca0)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_result_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff81d89ca0-ffffffff81d89d5e: uhci_free_td (STB_LOCAL)
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
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a66fe0)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffff800010a66fe0-ffff800010a670b0: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b38e8c)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
c0b38e8c-c0b38f64: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b380e0)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
c000000000b380e0-c000000000b381e8: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe0006810d0)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffe0006810d0-ffffffe000681176: uhci_free_td (STB_LOCAL)
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
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817e3b90)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff817e3b90-ffffffff817e3c3a: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81820630)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff81820630-ffffffff818206da: uhci_free_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uhci_free_td(struct uhci_hcd *uhci, struct uhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8183a740)
Location: drivers/usb/host/uhci-q.c:124
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_free_urb_priv
  - drivers/usb/host/uhci-hcd.c:uhci_make_qh_idle
  - drivers/usb/host/uhci-hcd.c:uhci_free_qh
```
**Symbols:**

```
ffffffff8183a740-ffffffff8183a7ea: uhci_free_td (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
