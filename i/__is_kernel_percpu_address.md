# Function: <code>__is_kernel_percpu_address</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e4980)
Location: mm/percpu.c:1289
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff811e4980-ffffffff811e4a28: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811fac40)
Location: mm/percpu.c:1735
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff811fac40-ffffffff811facdd: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121bf00)
Location: mm/percpu.c:1745
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff8121bf00-ffffffff8121bf9d: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122eee0)
Location: mm/percpu.c:1756
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff8122eee0-ffffffff8122ef7d: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123eed0)
Location: mm/percpu.c:1997
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff8123eed0-ffffffff8123ef72: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124d330)
Location: mm/percpu.c:1997
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff8124d330-ffffffff8124d3d2: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8127b725)
Location: mm/percpu.c:1974
Inline: True
Inline callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff8127b670-ffffffff8127b712: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81286276)
Location: mm/percpu.c:2127
Inline: True
Inline callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff812861a0-ffffffff81286242: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8128b52f)
Location: mm/percpu.c:2128
Inline: True
Inline callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff8128b450-ffffffff8128b4fc: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812cb280)
Location: mm/percpu.c:2315
Inline: True
Inline callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff812cb140-ffffffff812cb247: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81328c8f)
Location: mm/percpu.c:2313
Inline: True
Inline callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff81328b30-ffffffff81328c51: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139ddb0)
Location: mm/percpu.c:2305
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff8139ddb0-ffffffff8139ded2: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813d0f10)
Location: mm/percpu.c:2305
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff813d0f10-ffffffff813d1032: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813fb940)
Location: mm/percpu.c:2334
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff813fb940-ffffffff813fba62: __is_kernel_percpu_address (STB_GLOBAL)
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
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e3c28)
Location: mm/percpu.c:1997
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffff8000102e3c28-ffff8000102e3d14: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0507f24)
Location: mm/percpu.c:1997
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
c0507f24-c0507ff0: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a4250)
Location: mm/percpu.c:1997
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
c0000000003a4250-c0000000003a438c: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001fa546)
Location: mm/percpu.c:1997
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffe0001fa546-ffffffe0001fa604: __is_kernel_percpu_address (STB_GLOBAL)
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
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81245980)
Location: mm/percpu.c:1997
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff81245980-ffffffff81245a22: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81238930)
Location: mm/percpu.c:1997
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff81238930-ffffffff812389d2: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81243720)
Location: mm/percpu.c:1997
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff81243720-ffffffff812437c2: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __is_kernel_percpu_address(long unsigned int addr, long unsigned int *can_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81252ee0)
Location: mm/percpu.c:1997
Inline: False
Direct callers:
  - mm/percpu.c:is_kernel_percpu_address
```
**Symbols:**

```
ffffffff81252ee0-ffffffff81252f82: __is_kernel_percpu_address (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
