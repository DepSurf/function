# Function: <code>badrange_forget</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff816a2540)
Location: drivers/nvdimm/badrange.c:109
Inline: False
```
**Symbols:**

```
ffffffff816a2540-ffffffff816a26f3: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff816de7a0)
Location: drivers/nvdimm/badrange.c:109
Inline: False
```
**Symbols:**

```
ffffffff816de7a0-ffffffff816de980: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81700a80)
Location: drivers/nvdimm/badrange.c:109
Inline: False
```
**Symbols:**

```
ffffffff81700a80-ffffffff81700c61: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8173a8f0)
Location: drivers/nvdimm/badrange.c:101
Inline: False
```
**Symbols:**

```
ffffffff8173a8f0-ffffffff8173aadc: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8175e5c0)
Location: drivers/nvdimm/badrange.c:101
Inline: False
```
**Symbols:**

```
ffffffff8175e5c0-ffffffff8175e7ac: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8181e0f0)
Location: drivers/nvdimm/badrange.c:101
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff8181e0f0-ffffffff8181e2dc: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8182d070)
Location: drivers/nvdimm/badrange.c:101
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff8182d070-ffffffff8182d25c: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81810470)
Location: drivers/nvdimm/badrange.c:101
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff81810470-ffffffff8181065f: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8189aaa0)
Location: drivers/nvdimm/badrange.c:101
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff8189aaa0-ffffffff8189ac8c: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff819e41e0)
Location: drivers/nvdimm/badrange.c:101
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff819e41e0-ffffffff819e4357: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81b5fef0)
Location: drivers/nvdimm/badrange.c:101
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff81b5fef0-ffffffff81b60067: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81bb3490)
Location: drivers/nvdimm/badrange.c:101
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff81bb3490-ffffffff81bb3607: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81c079b0)
Location: drivers/nvdimm/badrange.c:101
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
**Symbols:**

```
ffffffff81c079b0-ffffffff81c07b56: badrange_forget (STB_GLOBAL)
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
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffff80001095fce8)
Location: drivers/nvdimm/badrange.c:101
Inline: False
```
**Symbols:**

```
ffff80001095fce8-ffff80001095fec8: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (c000000000a128b0)
Location: drivers/nvdimm/badrange.c:101
Inline: False
```
**Symbols:**

```
c000000000a128b0-c000000000a12b20: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffe0005cd8aa)
Location: drivers/nvdimm/badrange.c:101
Inline: False
```
**Symbols:**

```
ffffffe0005cd8aa-ffffffe0005cda5e: badrange_forget (STB_GLOBAL)
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
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81712cb0)
Location: drivers/nvdimm/badrange.c:101
Inline: False
```
**Symbols:**

```
ffffffff81712cb0-ffffffff81712e9c: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff816e6730)
Location: drivers/nvdimm/badrange.c:101
Inline: False
```
**Symbols:**

```
ffffffff816e6730-ffffffff816e691c: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81751a80)
Location: drivers/nvdimm/badrange.c:101
Inline: False
```
**Symbols:**

```
ffffffff81751a80-ffffffff81751c6c: badrange_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void badrange_forget(struct badrange *badrange, phys_addr_t start, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8176cfe0)
Location: drivers/nvdimm/badrange.c:101
Inline: False
```
**Symbols:**

```
ffffffff8176cfe0-ffffffff8176d1ca: badrange_forget (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
