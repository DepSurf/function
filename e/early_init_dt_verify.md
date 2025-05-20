# Function: <code>early_init_dt_verify</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
bool early_init_dt_verify(void *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffff8000114ab728)
Location: drivers/of/fdt.c:1172
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan
```
**Symbols:**

```
ffff8000114ab728-ffff8000114ab790: early_init_dt_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool early_init_dt_verify(void *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c15afe54)
Location: drivers/of/fdt.c:1172
Inline: False
Direct callers:
  - arch/arm/kernel/devtree.c:setup_machine_fdt
  - drivers/of/fdt.c:early_init_dt_scan
```
**Symbols:**

```
c15afe54-c15afebc: early_init_dt_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool early_init_dt_verify(void *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (c0000000013bb8d0)
Location: drivers/of/fdt.c:1172
Inline: False
Direct callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
  - arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_init
  - drivers/of/fdt.c:early_init_dt_scan
```
**Symbols:**

```
c0000000013bb8d0-c0000000013bb95c: early_init_dt_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool early_init_dt_verify(void *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/fdt.c (ffffffe00003ba0a)
Location: drivers/of/fdt.c:1172
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan
```
**Symbols:**

```
ffffffe00003ba0a-ffffffe00003ba80: early_init_dt_verify (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
