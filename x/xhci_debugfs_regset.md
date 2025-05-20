# Function: <code>xhci_debugfs_regset</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81776070)
Location: drivers/usb/host/xhci-debugfs.c:112
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff81776070-ffffffff8177619e: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b6bf0)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff817b6bf0-ffffffff817b6d05: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dcf60)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff817dcf60-ffffffff817dd075: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181d120)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff8181d120-ffffffff8181d22c: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184e4e0)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff8184e4e0-ffffffff8184e5ec: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81921b30)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff81921b30-ffffffff81921c3c: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81929180)
Location: drivers/usb/host/xhci-debugfs.c:114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff81929180-ffffffff8192928c: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190c800)
Location: drivers/usb/host/xhci-debugfs.c:114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff8190c800-ffffffff8190c909: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ad1d0)
Location: drivers/usb/host/xhci-debugfs.c:114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff819ad1d0-ffffffff819ad2d9: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0b7e0)
Location: drivers/usb/host/xhci-debugfs.c:114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff81b0b7e0-ffffffff81b0b91d: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9b760)
Location: drivers/usb/host/xhci-debugfs.c:114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff81c9b760-ffffffff81c9b89d: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d02b40)
Location: drivers/usb/host/xhci-debugfs.c:114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff81d02b40-ffffffff81d02c84: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db8670)
Location: drivers/usb/host/xhci-debugfs.c:114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff81db8670-ffffffff81db87e3: xhci_debugfs_regset (STB_LOCAL)
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
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8ec78)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffff800010a8ec78-ffff800010a8eda4: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (c0b61d9c)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
c0b61d9c-c0b61e8c: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (c000000000b6b210)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
c000000000b6b210-c000000000b6b324: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a26b2)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffe0006a26b2-ffffffe0006a2784: xhci_debugfs_regset (STB_LOCAL)
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
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff818042b0)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff818042b0-ffffffff818043bc: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cba30)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff817cba30-ffffffff817cbb3c: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff81843360)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff81843360-ffffffff8184346c: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xhci_debugfs_regset(struct xhci_hcd *xhci, u32 base, const struct debugfs_reg32 *regs, size_t nregs, struct dentry *parent, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185d8c0)
Location: drivers/usb/host/xhci-debugfs.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_init
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
**Symbols:**

```
ffffffff8185d8c0-ffffffff8185d9cc: xhci_debugfs_regset (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
