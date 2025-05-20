# Function: <code>setup_boot_config</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff82cc2da6)
Location: init/main.c:395
Inline: True
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff82cc2da6-ffffffff82cc2ff8: setup_boot_config.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff82faf081)
Location: init/main.c:407
Inline: True
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff82faf081-ffffffff82faf279: setup_boot_config.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void setup_boot_config();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff831b8ca8)
Location: init/main.c:408
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff831b8ca8-ffffffff831b8f16: setup_boot_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void setup_boot_config();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff832992d5)
Location: init/main.c:407
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff832992d5-ffffffff83299568: setup_boot_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void setup_boot_config();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff834474c4)
Location: init/main.c:411
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff834474c4-ffffffff83447742: setup_boot_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void setup_boot_config();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83e60b40)
Location: init/main.c:414
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff83e60b40-ffffffff83e60df7: setup_boot_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void setup_boot_config();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83681020)
Location: init/main.c:404
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff83681020-ffffffff83681310: setup_boot_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void setup_boot_config();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff838b0040)
Location: init/main.c:404
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff838b0040-ffffffff838b0330: setup_boot_config (STB_LOCAL)
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
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
