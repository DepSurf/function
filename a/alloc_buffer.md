# Function: <code>alloc_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81635690)
Location: drivers/usb/host/ehci-dbg.c:939
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81642330)
Location: drivers/usb/host/ohci-dbg.c:664
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff81635690-ffffffff816356f2: alloc_buffer (STB_LOCAL)
ffffffff81642330-ffffffff8164238a: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816962c0)
Location: drivers/usb/host/ehci-dbg.c:925
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816a2e30)
Location: drivers/usb/host/ohci-dbg.c:664
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff816962c0-ffffffff81696322: alloc_buffer (STB_LOCAL)
ffffffff816a2e30-ffffffff816a2e8a: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c41e0)
Location: drivers/usb/host/ehci-dbg.c:925
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816d0f30)
Location: drivers/usb/host/ohci-dbg.c:664
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff816c41e0-ffffffff816c4242: alloc_buffer (STB_LOCAL)
ffffffff816d0f30-ffffffff816d0f8a: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816d89a0)
Location: drivers/usb/host/ehci-dbg.c:925
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e55c0)
Location: drivers/usb/host/ohci-dbg.c:664
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff816d89a0-ffffffff816d8a08: alloc_buffer (STB_LOCAL)
ffffffff816e55c0-ffffffff816e5620: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817450d0)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81751de0)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff817450d0-ffffffff81745138: alloc_buffer (STB_LOCAL)
ffffffff81751de0-ffffffff81751e40: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81785810)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81791840)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff81785810-ffffffff81785872: alloc_buffer (STB_LOCAL)
ffffffff81791840-ffffffff8179189a: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817a9030)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817b5720)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff817a9030-ffffffff817a9092: alloc_buffer (STB_LOCAL)
ffffffff817b5720-ffffffff817b577a: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817e8230)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817f4d20)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff817e8230-ffffffff817e8293: alloc_buffer (STB_LOCAL)
ffffffff817f4d20-ffffffff817f4d7a: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81819100)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81825b80)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff81819100-ffffffff81819163: alloc_buffer (STB_LOCAL)
ffffffff81825b80-ffffffff81825bda: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818ed302)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818f8872)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f6222)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff819013b2)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818d9ff2)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e4b12)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff819755b2)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff819814b2)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad1032)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adce32)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5b9e2)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c68db2)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc3292)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81ccf502)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7821e)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d850ae)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a52350)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a5fd90)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffff800010a52350-ffff800010a523c4: alloc_buffer (STB_LOCAL)
ffff800010a5fd90-ffff800010a5fdfc: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b24e78)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (c0b32238)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
c0b24e78-c0b24ee4: alloc_buffer (STB_LOCAL)
c0b32238-c0b3229c: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b1eed0)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b2efc0)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
c000000000b1eed0-c000000000b1ef70: alloc_buffer (STB_LOCAL)
c000000000b2efc0-c000000000b2f058: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe00066e72a)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067af26)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffe00066e72a-ffffffe00066e79e: alloc_buffer (STB_LOCAL)
ffffffe00067af26-ffffffe00067af92: alloc_buffer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d14e0)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817ddf60)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff817d14e0-ffffffff817d1543: alloc_buffer (STB_LOCAL)
ffffffff817ddf60-ffffffff817ddfba: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8180df80)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8181aa00)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff8180df80-ffffffff8180dfe3: alloc_buffer (STB_LOCAL)
ffffffff8181aa00-ffffffff8181aa5a: alloc_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
struct debug_buffer *alloc_buffer(struct usb_bus *bus, ssize_t (*fill_func)(struct debug_buffer *));
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81828680)
Location: drivers/usb/host/ehci-dbg.c:915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81834b50)
Location: drivers/usb/host/ohci-dbg.c:665
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
```
**Symbols:**

```
ffffffff81828680-ffffffff818286e3: alloc_buffer (STB_LOCAL)
ffffffff81834b50-ffffffff81834baa: alloc_buffer (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
