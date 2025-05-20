# Function: <code>xhci_test_trb_in_td</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816524e0)
Location: drivers/usb/host/xhci-mem.c:1872
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff816524e0-ffffffff816525ed: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b2df0)
Location: drivers/usb/host/xhci-mem.c:1894
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff816b2df0-ffffffff816b2efd: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e0fa0)
Location: drivers/usb/host/xhci-mem.c:1927
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff816e0fa0-ffffffff816e10ad: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f5170)
Location: drivers/usb/host/xhci-mem.c:1866
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff816f5170-ffffffff816f527d: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81761b80)
Location: drivers/usb/host/xhci-mem.c:1908
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff81761b80-ffffffff81761c8d: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a2540)
Location: drivers/usb/host/xhci-mem.c:1929
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff817a2540-ffffffff817a264b: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817c8830)
Location: drivers/usb/host/xhci-mem.c:1929
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff817c8830-ffffffff817c893b: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:1929
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff818086b0-ffffffff81808729: xhci_test_trb_in_td (STB_LOCAL)
ffffffff8180c6de-ffffffff8180c772: xhci_test_trb_in_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:1939
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff81839570-ffffffff818395e9: xhci_test_trb_in_td (STB_LOCAL)
ffffffff8183d6d0-ffffffff8183d764: xhci_test_trb_in_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:1939
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff8190bfc0-ffffffff8190c039: xhci_test_trb_in_td (STB_LOCAL)
ffffffff81910034-ffffffff819100c8: xhci_test_trb_in_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:1947
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff81913a40-ffffffff81913ab9: xhci_test_trb_in_td (STB_LOCAL)
ffffffff81c216e3-ffffffff81c21777: xhci_test_trb_in_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:1935
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff818f6f50-ffffffff818f6fc9: xhci_test_trb_in_td (STB_LOCAL)
ffffffff81c13791-ffffffff81c13822: xhci_test_trb_in_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:1935
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff81995360-ffffffff819953d9: xhci_test_trb_in_td (STB_LOCAL)
ffffffff81d205b7-ffffffff81d20648: xhci_test_trb_in_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:1923
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff81af2070-ffffffff81af20fb: xhci_test_trb_in_td (STB_LOCAL)
ffffffff81eec105-ffffffff81eec197: xhci_test_trb_in_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c7f350)
Location: drivers/usb/host/xhci-mem.c:1932
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff81c7f350-ffffffff81c7f46b: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a770f8)
Location: drivers/usb/host/xhci-mem.c:1939
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffff800010a770f8-ffff800010a77248: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4abbc)
Location: drivers/usb/host/xhci-mem.c:1939
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
c0b4abbc-c0b4acf8: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b4d830)
Location: drivers/usb/host/xhci-mem.c:1939
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
c000000000b4d830-c000000000b4d9dc: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe00068ebc6)
Location: drivers/usb/host/xhci-mem.c:1939
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffe00068ebc6-ffffffe00068ecd8: xhci_test_trb_in_td (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:1939
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff817f1920-ffffffff817f1999: xhci_test_trb_in_td (STB_LOCAL)
ffffffff817f5a80-ffffffff817f5b14: xhci_test_trb_in_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:1939
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff817b6ac0-ffffffff817b6b39: xhci_test_trb_in_td (STB_LOCAL)
ffffffff817bac20-ffffffff817bacb4: xhci_test_trb_in_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:1939
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff8182e3f0-ffffffff8182e469: xhci_test_trb_in_td (STB_LOCAL)
ffffffff81832550-ffffffff818325e4: xhci_test_trb_in_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_test_trb_in_td(struct xhci_hcd *xhci, struct xhci_segment *input_seg, union xhci_trb *start_trb, union xhci_trb *end_trb, dma_addr_t input_dma, struct xhci_segment *result_seg, char *test_name, int test_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:1939
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
  - drivers/usb/host/xhci-mem.c:xhci_check_trb_in_td_math
```
**Symbols:**

```
ffffffff818484e0-ffffffff81848559: xhci_test_trb_in_td (STB_LOCAL)
ffffffff8184c730-ffffffff8184c7c4: xhci_test_trb_in_td.cold (STB_LOCAL)
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
