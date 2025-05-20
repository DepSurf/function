# Function: <code>hvm_get_parameter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff814cedb0)
Location: include/xen/hvm.h:38
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff52d)
Location: include/xen/hvm.h:38
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff814cedb0-ffffffff814cee4c: hvm_get_parameter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8151f9b0)
Location: include/xen/hvm.h:38
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815503f8)
Location: include/xen/hvm.h:38
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff8151f9b0-ffffffff8151fa4c: hvm_get_parameter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8154be60)
Location: include/xen/hvm.h:38
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157cc78)
Location: include/xen/hvm.h:38
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff8154be60-ffffffff8154befc: hvm_get_parameter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81560040)
Location: include/xen/hvm.h:38
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590edd)
Location: include/xen/hvm.h:38
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff81560040-ffffffff815600cd: hvm_get_parameter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c42e0)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f5a2d)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff815c42e0-ffffffff815c436d: hvm_get_parameter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fd5e4)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162eb4b)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff815fc9b0-ffffffff815fca17: hvm_get_parameter (STB_LOCAL)
ffffffff815fd631-ffffffff815fd660: hvm_get_parameter.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816186c4)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164cd8b)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff81617ad0-ffffffff81617b37: hvm_get_parameter (STB_LOCAL)
ffffffff81618733-ffffffff81618762: hvm_get_parameter.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164c376)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816818a1)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff8164b780-ffffffff8164b7e7: hvm_get_parameter (STB_LOCAL)
ffffffff8164c3e6-ffffffff8164c422: hvm_get_parameter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166e806)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3f51)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff8166dc10-ffffffff8166dc77: hvm_get_parameter (STB_LOCAL)
ffffffff8166e876-ffffffff8166e8b2: hvm_get_parameter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171e9a6)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8175674e)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff8171e2d0-ffffffff8171e336: hvm_get_parameter (STB_LOCAL)
ffffffff8171ebef-ffffffff8171ec1c: hvm_get_parameter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8173ba06)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817719be)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff8173b250-ffffffff8173b2b6: hvm_get_parameter (STB_LOCAL)
ffffffff81c055eb-ffffffff81c05618: hvm_get_parameter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171f572)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755464)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff8171ed90-ffffffff8171edf8: hvm_get_parameter (STB_LOCAL)
ffffffff81bf7264-ffffffff81bf7292: hvm_get_parameter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8179e392)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d8b94)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff8179db40-ffffffff8179dc0b: hvm_get_parameter (STB_LOCAL)
ffffffff81cf6170-ffffffff81cf617c: hvm_get_parameter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff818d7e61)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81916efc)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff818d7400-ffffffff818d74e9: hvm_get_parameter (STB_LOCAL)
ffffffff81ebe23f-ffffffff81ebe24b: hvm_get_parameter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83eeb09f)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a722e2)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83710aaf)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abcba2)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8394442f)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0f992)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffff800010838c50)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffff80001087c2c4)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffff800010838c50-ffff800010838d00: hvm_get_parameter (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816347f6)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816699b1)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff81633a20-ffffffff81633a87: hvm_get_parameter (STB_LOCAL)
ffffffff81634845-ffffffff81634881: hvm_get_parameter.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81662646)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697d91)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff81661a50-ffffffff81661ab7: hvm_get_parameter (STB_LOCAL)
ffffffff816626b6-ffffffff816626f2: hvm_get_parameter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int hvm_get_parameter(int idx, uint64_t *value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167cc16)
Location: include/xen/hvm.h:39
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b2311)
Location: include/xen/hvm.h:39
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffffffff8167c020-ffffffff8167c087: hvm_get_parameter (STB_LOCAL)
ffffffff8167cc86-ffffffff8167ccc2: hvm_get_parameter.cold (STB_LOCAL)
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
