# Function: <code>xenbus_probe_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff814cf2a0)
Location: drivers/xen/xenbus/xenbus_probe.c:426
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff814cf2a0-ffffffff814cf42e: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8151fea0)
Location: drivers/xen/xenbus/xenbus_probe.c:426
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff8151fea0-ffffffff81520033: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8154c350)
Location: drivers/xen/xenbus/xenbus_probe.c:426
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff8154c350-ffffffff8154c4e3: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81560630)
Location: drivers/xen/xenbus/xenbus_probe.c:422
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff81560630-ffffffff8156079d: xenbus_probe_node.part.7 (STB_LOCAL)
ffffffff815607a0-ffffffff815607df: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c48f0)
Location: drivers/xen/xenbus/xenbus_probe.c:422
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff815c48f0-ffffffff815c4a62: xenbus_probe_node.part.7 (STB_LOCAL)
ffffffff815c4a70-ffffffff815c4aaf: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fcf70)
Location: drivers/xen/xenbus/xenbus_probe.c:422
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff815fcf70-ffffffff815fd0f0: xenbus_probe_node.part.7 (STB_LOCAL)
ffffffff815fd0f0-ffffffff815fd12f: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81618050)
Location: drivers/xen/xenbus/xenbus_probe.c:431
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff81618050-ffffffff816181d0: xenbus_probe_node.part.7 (STB_LOCAL)
ffffffff816181d0-ffffffff8161820f: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164bd20)
Location: drivers/xen/xenbus/xenbus_probe.c:431
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff8164bd20-ffffffff8164bea7: xenbus_probe_node.part.0 (STB_LOCAL)
ffffffff8164beb0-ffffffff8164bef1: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166e1b0)
Location: drivers/xen/xenbus/xenbus_probe.c:431
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff8166e1b0-ffffffff8166e337: xenbus_probe_node.part.0 (STB_LOCAL)
ffffffff8166e340-ffffffff8166e381: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171ebb3)
Location: drivers/xen/xenbus/xenbus_probe.c:432
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff8171e470-ffffffff8171e5fe: xenbus_probe_node.part.0 (STB_LOCAL)
ffffffff8171e600-ffffffff8171e641: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8173bc13)
Location: drivers/xen/xenbus/xenbus_probe.c:433
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff8173b3f0-ffffffff8173b57e: xenbus_probe_node.part.0 (STB_LOCAL)
ffffffff8173b580-ffffffff8173b5c1: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171f772)
Location: drivers/xen/xenbus/xenbus_probe.c:499
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff8171ef40-ffffffff8171f0ce: xenbus_probe_node.part.0 (STB_LOCAL)
ffffffff8171f0d0-ffffffff8171f111: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8179e592)
Location: drivers/xen/xenbus/xenbus_probe.c:496
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff8179dd60-ffffffff8179deee: xenbus_probe_node.part.0 (STB_LOCAL)
ffffffff8179def0-ffffffff8179df31: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff818d7730)
Location: drivers/xen/xenbus/xenbus_probe.c:497
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff818d7730-ffffffff818d78e5: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a29ce0)
Location: drivers/xen/xenbus/xenbus_probe.c:497
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff81a29ce0-ffffffff81a29e95: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a733e0)
Location: drivers/xen/xenbus/xenbus_probe.c:497
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff81a733e0-ffffffff81a73638: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ac5540)
Location: drivers/xen/xenbus/xenbus_probe.c:497
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff81ac5540-ffffffff81ac5797: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffff800010838ef8)
Location: drivers/xen/xenbus/xenbus_probe.c:431
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffff800010838ef8-ffff80001083905c: xenbus_probe_node.part.0 (STB_LOCAL)
ffff800010839060-ffff8000108390c8: xenbus_probe_node (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81633fd0)
Location: drivers/xen/xenbus/xenbus_probe.c:432
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff81633fd0-ffffffff81634157: xenbus_probe_node.part.0 (STB_LOCAL)
ffffffff81634160-ffffffff816341a1: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81661ff0)
Location: drivers/xen/xenbus/xenbus_probe.c:431
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff81661ff0-ffffffff81662177: xenbus_probe_node.part.0 (STB_LOCAL)
ffffffff81662180-ffffffff816621c1: xenbus_probe_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_probe_node(struct xen_bus_type *bus, const char *type, const char *nodename);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167c5c0)
Location: drivers/xen/xenbus/xenbus_probe.c:431
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_probe_frontend
```
**Symbols:**

```
ffffffff8167c5c0-ffffffff8167c747: xenbus_probe_node.part.0 (STB_LOCAL)
ffffffff8167c750-ffffffff8167c791: xenbus_probe_node (STB_GLOBAL)
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
