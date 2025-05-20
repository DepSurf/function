# Function: <code>early_platform_driver_setup_func</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int early_platform_driver_setup_func(char *buffer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/sh_cmt.c (ffff8000114a811c)
Location: drivers/clocksource/sh_cmt.c:1112
Inline: False
```
```
In drivers/clocksource/sh_tmu.c (ffff8000114a8178)
Location: drivers/clocksource/sh_tmu.c:668
Inline: False
```
**Symbols:**

```
ffff8000114a811c-ffff8000114a8150: early_platform_driver_setup_func (STB_LOCAL)
ffff8000114a8178-ffff8000114a81ac: early_platform_driver_setup_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int early_platform_driver_setup_func(char *buffer);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/sh_cmt.c (c15aa6f0)
Location: drivers/clocksource/sh_cmt.c:1112
Inline: False
```
```
In drivers/clocksource/sh_mtu2.c (c15aa740)
Location: drivers/clocksource/sh_mtu2.c:520
Inline: False
```
```
In drivers/clocksource/sh_tmu.c (c15aaa78)
Location: drivers/clocksource/sh_tmu.c:668
Inline: False
```
**Symbols:**

```
c15aa6f0-c15aa718: early_platform_driver_setup_func (STB_LOCAL)
c15aa740-c15aa768: early_platform_driver_setup_func (STB_LOCAL)
c15aaa78-c15aaaa0: early_platform_driver_setup_func (STB_LOCAL)
```
</details>
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
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
