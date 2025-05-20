# Function: <code>nvdimm_security_store</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81761ff0)
Location: drivers/nvdimm/security.c:495
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff81761ff0-ffffffff81762aec: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff818225b0)
Location: drivers/nvdimm/security.c:500
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff818225b0-ffffffff81822894: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff818312c0)
Location: drivers/nvdimm/security.c:500
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff818312c0-ffffffff818315a4: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81814370)
Location: drivers/nvdimm/security.c:500
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff81814370-ffffffff818147dc: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:500
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff81d0b848-ffffffff81d0b85d: nvdimm_security_store.cold (STB_LOCAL)
ffffffff8189ea30-ffffffff8189ef9e: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/security.c (0)
Location: drivers/nvdimm/security.c:495
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff81ed46c1-ffffffff81ed46dc: nvdimm_security_store.cold (STB_LOCAL)
ffffffff819e84e0-ffffffff819e8a96: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81b64ad0)
Location: drivers/nvdimm/security.c:521
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff81b64ad0-ffffffff81b64f1b: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81bb80d0)
Location: drivers/nvdimm/security.c:521
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff81bb80d0-ffffffff81bb851b: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81c0c720)
Location: drivers/nvdimm/security.c:521
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff81c0c720-ffffffff81c0cb6b: nvdimm_security_store (STB_GLOBAL)
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
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffff800010961ee8)
Location: drivers/nvdimm/security.c:495
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffff800010961ee8-ffff800010962878: nvdimm_security_store (STB_GLOBAL)
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
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (c000000000a17dd0)
Location: drivers/nvdimm/security.c:495
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
c000000000a17dd0-c000000000a18998: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffe0005cf6a8)
Location: drivers/nvdimm/security.c:495
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffe0005cf6a8-ffffffe0005cfef2: nvdimm_security_store (STB_GLOBAL)
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
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff817166e0)
Location: drivers/nvdimm/security.c:495
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff817166e0-ffffffff817171dc: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff816ea160)
Location: drivers/nvdimm/security.c:495
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff816ea160-ffffffff816eac5c: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff817554b0)
Location: drivers/nvdimm/security.c:495
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff817554b0-ffffffff81755fac: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t nvdimm_security_store(struct device *dev, const char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/security.c (ffffffff81770920)
Location: drivers/nvdimm/security.c:495
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:security_store
```
**Symbols:**

```
ffffffff81770920-ffffffff8177141c: nvdimm_security_store (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
