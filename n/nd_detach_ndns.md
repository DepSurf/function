# Function: <code>nd_detach_ndns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff815a0b90)
Location: drivers/nvdimm/claim.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
```
**Symbols:**

```
ffffffff815a0b90-ffffffff815a0bea: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff815f6ee0)
Location: drivers/nvdimm/claim.c:33
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff815f6ee0-ffffffff815f6f3a: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81625150)
Location: drivers/nvdimm/claim.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81625150-ffffffff816251aa: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8163a110)
Location: drivers/nvdimm/claim.c:37
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8163a110-ffffffff8163a162: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff816a2d10)
Location: drivers/nvdimm/claim.c:37
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff816a2d10-ffffffff816a2d62: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff816dee90)
Location: drivers/nvdimm/claim.c:37
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff816dee90-ffffffff816deee2: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81701270)
Location: drivers/nvdimm/claim.c:37
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81701270-ffffffff817012c2: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8173b0f0)
Location: drivers/nvdimm/claim.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8173b0f0-ffffffff8173b144: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8175edc0)
Location: drivers/nvdimm/claim.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8175edc0-ffffffff8175ee14: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8181e7a0)
Location: drivers/nvdimm/claim.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8181e7a0-ffffffff8181e7f4: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8182d6e0)
Location: drivers/nvdimm/claim.c:30
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8182d6e0-ffffffff8182d734: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff818109d0)
Location: drivers/nvdimm/claim.c:30
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff818109d0-ffffffff81810a24: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8189b020)
Location: drivers/nvdimm/claim.c:30
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8189b020-ffffffff8189b074: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff819e4760)
Location: drivers/nvdimm/claim.c:30
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff819e4760-ffffffff819e47bc: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81b604c0)
Location: drivers/nvdimm/claim.c:30
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81b604c0-ffffffff81b6051c: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81bb3a50)
Location: drivers/nvdimm/claim.c:30
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81bb3a50-ffffffff81bb3aac: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81c07fa0)
Location: drivers/nvdimm/claim.c:30
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81c07fa0-ffffffff81c07ffc: nd_detach_ndns (STB_GLOBAL)
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
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffff8000109605b8)
Location: drivers/nvdimm/claim.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffff8000109605b8-ffff800010960620: nd_detach_ndns (STB_GLOBAL)
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
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (c000000000a135a0)
Location: drivers/nvdimm/claim.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
c000000000a135a0-c000000000a13638: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffe0005ce010)
Location: drivers/nvdimm/claim.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
```
**Symbols:**

```
ffffffe0005ce010-ffffffe0005ce076: nd_detach_ndns (STB_GLOBAL)
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
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff817134b0)
Location: drivers/nvdimm/claim.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff817134b0-ffffffff81713504: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff816e6f30)
Location: drivers/nvdimm/claim.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff816e6f30-ffffffff816e6f84: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81752280)
Location: drivers/nvdimm/claim.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81752280-ffffffff817522d4: nd_detach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nd_detach_ndns(struct device *dev, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8176d6f0)
Location: drivers/nvdimm/claim.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8176d6f0-ffffffff8176d744: nd_detach_ndns (STB_GLOBAL)
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
