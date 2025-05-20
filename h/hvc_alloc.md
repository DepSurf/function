# Function: <code>hvc_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff814fdfb0)
Location: drivers/tty/hvc/hvc_console.c:858
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff814fdfb0-ffffffff814fe30c: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8154eae0)
Location: drivers/tty/hvc/hvc_console.c:858
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff8154eae0-ffffffff8154ee3e: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8157b360)
Location: drivers/tty/hvc/hvc_console.c:858
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff8157b360-ffffffff8157b6be: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8158fa10)
Location: drivers/tty/hvc/hvc_console.c:857
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff8158fa10-ffffffff8158fd23: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff815f4510)
Location: drivers/tty/hvc/hvc_console.c:844
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff815f4510-ffffffff815f4826: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:844
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff8162da20-ffffffff8162da5f: hvc_alloc.cold.13 (STB_LOCAL)
ffffffff8162d2e0-ffffffff8162d5ce: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:922
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff8164bca0-ffffffff8164bcdf: hvc_alloc.cold.15 (STB_LOCAL)
ffffffff8164b410-ffffffff8164b6fc: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:922
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff816807c0-ffffffff81680823: hvc_alloc.cold (STB_LOCAL)
ffffffff81680410-ffffffff816806de: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:922
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff816a2e70-ffffffff816a2ed3: hvc_alloc.cold (STB_LOCAL)
ffffffff816a2ac0-ffffffff816a2d8e: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff817548a0)
Location: drivers/tty/hvc/hvc_console.c:911
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff817548a0-ffffffff81754aaa: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8176fba0)
Location: drivers/tty/hvc/hvc_console.c:911
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff8176fba0-ffffffff8176fdaa: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:911
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff81bf9703-ffffffff81bf9774: hvc_alloc.cold (STB_LOCAL)
ffffffff81753550-ffffffff8175385c: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:911
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff81cf987c-ffffffff81cf98d3: hvc_alloc.cold (STB_LOCAL)
ffffffff817d6980-ffffffff817d6d32: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:911
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff81ec1ac2-ffffffff81ec1b22: hvc_alloc.cold (STB_LOCAL)
ffffffff81914a60-ffffffff81914e2c: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81a6fc40)
Location: drivers/tty/hvc/hvc_console.c:911
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff81a6fc40-ffffffff81a70070: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba3f0)
Location: drivers/tty/hvc/hvc_console.c:911
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff81aba3f0-ffffffff81aba82b: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d130)
Location: drivers/tty/hvc/hvc_console.c:911
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff81b0d130-ffffffff81b0d576: hvc_alloc (STB_GLOBAL)
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
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffff800010879c28)
Location: drivers/tty/hvc/hvc_console.c:922
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffff800010879c28-ffff800010879f24: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (c097ce5c)
Location: drivers/tty/hvc/hvc_console.c:922
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
c097ce5c-c097d138: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (c000000000922240)
Location: drivers/tty/hvc/hvc_console.c:922
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_vio.c:hvc_vio_probe
  - drivers/tty/hvc/hvc_opal.c:hvc_opal_probe
  - drivers/tty/hvc/hvc_rtas.c:hvc_rtas_init
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
c000000000922240-c00000000092260c: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffe00054ad08)
Location: drivers/tty/hvc/hvc_console.c:922
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_riscv_sbi.c:hvc_sbi_init
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffe00054ad08-ffffffe00054aff6: hvc_alloc (STB_GLOBAL)
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
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:922
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff816688d0-ffffffff81668933: hvc_alloc.cold (STB_LOCAL)
ffffffff81668520-ffffffff816687ee: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:922
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff81648c50-ffffffff81648cb3: hvc_alloc.cold (STB_LOCAL)
ffffffff816488a0-ffffffff81648b6e: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:922
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff81696cb0-ffffffff81696d13: hvc_alloc.cold (STB_LOCAL)
ffffffff81696900-ffffffff81696bce: hvc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct hvc_struct *hvc_alloc(uint32_t vtermno, int data, const struct hv_ops *ops, int outbuf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:922
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/char/virtio_console.c:init_port_console
```
**Symbols:**

```
ffffffff816b1260-ffffffff816b12c3: hvc_alloc.cold (STB_LOCAL)
ffffffff816b0eb0-ffffffff816b117e: hvc_alloc (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
