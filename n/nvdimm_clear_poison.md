# Function: <code>nvdimm_clear_poison</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ed310)
Location: drivers/nvdimm/bus.c:174
Inline: False
```
**Symbols:**

```
ffffffff815ed310-ffffffff815ed427: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8161a100)
Location: drivers/nvdimm/bus.c:174
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8161a100-ffffffff8161a239: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162e1b0)
Location: drivers/nvdimm/bus.c:230
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8162e1b0-ffffffff8162e356: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81696970)
Location: drivers/nvdimm/bus.c:231
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81696970-ffffffff81696b20: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d2ad0)
Location: drivers/nvdimm/bus.c:234
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff816d2ad0-ffffffff816d2c82: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f4220)
Location: drivers/nvdimm/bus.c:228
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff816f4220-ffffffff816f43d2: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172d810)
Location: drivers/nvdimm/bus.c:227
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8172d810-ffffffff8172d9b4: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81751ab0)
Location: drivers/nvdimm/bus.c:225
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81751ab0-ffffffff81751c54: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81810300)
Location: drivers/nvdimm/bus.c:225
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81810300-ffffffff818104eb: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181f240)
Location: drivers/nvdimm/bus.c:225
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8181f240-ffffffff8181f426: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81802560)
Location: drivers/nvdimm/bus.c:224
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81802560-ffffffff81802746: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8188ca40)
Location: drivers/nvdimm/bus.c:223
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff8188ca40-ffffffff8188cc28: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff819d5f20)
Location: drivers/nvdimm/bus.c:214
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff819d5f20-ffffffff819d6154: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b50b20)
Location: drivers/nvdimm/bus.c:214
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81b50b20-ffffffff81b50d54: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba3fc0)
Location: drivers/nvdimm/bus.c:214
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81ba3fc0-ffffffff81ba41f4: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf81b0)
Location: drivers/nvdimm/bus.c:214
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81bf81b0-ffffffff81bf83e4: nvdimm_clear_poison (STB_GLOBAL)
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
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffff8000109521f8)
Location: drivers/nvdimm/bus.c:225
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffff8000109521f8-ffff80001095239c: nvdimm_clear_poison (STB_GLOBAL)
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
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009ff000)
Location: drivers/nvdimm/bus.c:225
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
c0000000009ff000-c0000000009ff238: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c1d72)
Location: drivers/nvdimm/bus.c:225
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffe0005c1d72-ffffffe0005c1ecc: nvdimm_clear_poison (STB_GLOBAL)
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
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817061a0)
Location: drivers/nvdimm/bus.c:225
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff817061a0-ffffffff81706344: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d9c20)
Location: drivers/nvdimm/bus.c:225
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/pmem.c:pmem_do_bvec
```
**Symbols:**

```
ffffffff816d9c20-ffffffff816d9dc4: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81744f70)
Location: drivers/nvdimm/bus.c:225
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff81744f70-ffffffff81745114: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int nvdimm_clear_poison(struct device *dev, phys_addr_t phys, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817603b0)
Location: drivers/nvdimm/bus.c:225
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
**Symbols:**

```
ffffffff817603b0-ffffffff81760554: nvdimm_clear_poison (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
