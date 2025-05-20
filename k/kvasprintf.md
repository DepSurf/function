# Function: <code>kvasprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff813f8c30)
Location: lib/kasprintf.c:14
Inline: False
Direct callers:
  - lib/kasprintf.c:kasprintf
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff813f8c30-ffffffff813f8cce: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8143fab0)
Location: lib/kasprintf.c:14
Inline: False
Direct callers:
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff8143fab0-ffffffff8143fb7d: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8145cbb0)
Location: lib/kasprintf.c:14
Inline: False
Direct callers:
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff8145cbb0-ffffffff8145cc7d: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81461df0)
Location: lib/kasprintf.c:14
Inline: False
Direct callers:
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff81461df0-ffffffff81461eb2: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8148dcd0)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff8148dcd0-ffffffff8148dd92: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff814c2a50)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff814c2a50-ffffffff814c2b12: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff814d7100)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff814d7100-ffffffff814d71c2: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81502f60)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/fs_context.c:logfc
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff81502f60-ffffffff81503021: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81520f00)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/fs_context.c:logfc
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff81520f00-ffffffff81520fc1: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81584110)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff81584110-ffffffff815841cf: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815a1220)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff815a1220-ffffffff815a12df: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815a80d0)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff815a80d0-ffffffff815a818f: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81611090)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff81611090-ffffffff8161114f: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff816dd0a0)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff816dd0a0-ffffffff816dd16c: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff817ccee0)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff817ccee0-ffffffff817ccfb1: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8180b2f0)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff8180b2f0-ffffffff8180b3c1: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81851ad0)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/gpu/drm/drm_crtc.c:__drm_crtc_init_with_planes
  - drivers/gpu/drm/drm_encoder.c:__drm_encoder_init
  - drivers/gpu/drm/drm_plane.c:__drm_universal_plane_init
```
**Symbols:**

```
ffffffff81851ad0-ffffffff81851ba1: kvasprintf (STB_GLOBAL)
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
char *kvasprintf(gfp_t gfp, const char *fmt, va_list ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffff80001062a538)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/fs_context.c:logfc
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffff80001062a538-ffff80001062a62c: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, va_list ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (c07d1788)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/fs_context.c:logfc
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
```
**Symbols:**

```
c07d1788-c07d1860: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, va_list ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (c0000000007cc530)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/fs_context.c:logfc
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
```
**Symbols:**

```
c0000000007cc530-c0000000007cc610: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, va_list ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffe00045af78)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/fs_context.c:logfc
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
```
**Symbols:**

```
ffffffe00045af78-ffffffe00045b006: kvasprintf (STB_GLOBAL)
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
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815194e0)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/fs_context.c:logfc
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff815194e0-ffffffff815195a1: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815097d0)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/fs_context.c:logfc
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
```
**Symbols:**

```
ffffffff815097d0-ffffffff81509891: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81515570)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/fs_context.c:logfc
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff81515570-ffffffff81515631: kvasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *kvasprintf(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8152ed00)
Location: lib/kasprintf.c:15
Inline: False
Direct callers:
  - fs/fs_context.c:logfc
  - fs/configfs/item.c:config_item_set_name
  - lib/kasprintf.c:kasprintf
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pci/irq.c:pci_request_irq
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
```
**Symbols:**

```
ffffffff8152ed00-ffffffff8152edc1: kvasprintf (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
</details>
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
