# Function: <code>of_setup_earlycon</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int of_setup_earlycon(long unsigned int addr, int (*setup)(struct earlycon_device *, const char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/earlycon.c (ffffffff81fa6fe0)
Location: drivers/tty/serial/earlycon.c:200
Inline: False
```
**Symbols:**

```
ffffffff81fa6fe0-ffffffff81fa7055: of_setup_earlycon (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int of_setup_earlycon(const struct earlycon_id *match, long unsigned int node, const char *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/earlycon.c (ffff800011494100)
Location: drivers/tty/serial/earlycon.c:231
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
```
**Symbols:**

```
ffff800011494100-ffff800011494348: of_setup_earlycon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_setup_earlycon(const struct earlycon_id *match, long unsigned int node, const char *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/earlycon.c (c15949c4)
Location: drivers/tty/serial/earlycon.c:231
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
```
**Symbols:**

```
c15949c4-c1594c34: of_setup_earlycon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_setup_earlycon(const struct earlycon_id *match, long unsigned int node, const char *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/earlycon.c (c0000000013a75a8)
Location: drivers/tty/serial/earlycon.c:231
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
```
**Symbols:**

```
c0000000013a75a8-c0000000013a78ec: of_setup_earlycon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_setup_earlycon(const struct earlycon_id *match, long unsigned int node, const char *options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/earlycon.c (ffffffe00002edec)
Location: drivers/tty/serial/earlycon.c:231
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen_stdout
```
**Symbols:**

```
ffffffe00002edec-ffffffe00002f076: of_setup_earlycon (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
