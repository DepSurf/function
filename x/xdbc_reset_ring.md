# Function: <code>xdbc_reset_ring</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff817df1b0)
Location: drivers/usb/early/xhci-dbc.c:198
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff817df1b0-ffffffff817df22a: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8181fc40)
Location: drivers/usb/early/xhci-dbc.c:198
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff8181fc40-ffffffff8181fcba: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff818510b0)
Location: drivers/usb/early/xhci-dbc.c:198
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff818510b0-ffffffff8185112a: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81923555)
Location: drivers/usb/early/xhci-dbc.c:197
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff81923090-ffffffff8192310a: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8192ab65)
Location: drivers/usb/early/xhci-dbc.c:192
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff8192a7c0-ffffffff8192a83a: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8190dfa5)
Location: drivers/usb/early/xhci-dbc.c:192
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff8190dce0-ffffffff8190dd5a: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff819aefa5)
Location: drivers/usb/early/xhci-dbc.c:199
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff819aeb00-ffffffff819aeb7a: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81b0d2a0)
Location: drivers/usb/early/xhci-dbc.c:199
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff81b0d2a0-ffffffff81b0d328: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81c9d320)
Location: drivers/usb/early/xhci-dbc.c:199
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff81c9d320-ffffffff81c9d3a8: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81d04730)
Location: drivers/usb/early/xhci-dbc.c:199
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff81d04730-ffffffff81d047b8: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff81dba2f0)
Location: drivers/usb/early/xhci-dbc.c:199
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff81dba2f0-ffffffff81dba378: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xdbc_reset_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff818604b0)
Location: drivers/usb/early/xhci-dbc.c:198
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
**Symbols:**

```
ffffffff818604b0-ffffffff8186052a: xdbc_reset_ring (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
