# Function: <code>__iommu_attach_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152b190)
Location: drivers/iommu/iommu.c:1201
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
```
**Symbols:**

```
ffffffff8152b190-ffffffff8152b202: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157e7e0)
Location: drivers/iommu/iommu.c:1191
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff8157e7e0-ffffffff8157e84c: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aada0)
Location: drivers/iommu/iommu.c:1342
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff815aada0-ffffffff815aae0c: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815bf610)
Location: drivers/iommu/iommu.c:1392
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff815bf610-ffffffff815bf684: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816261d0)
Location: drivers/iommu/iommu.c:1393
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff816261d0-ffffffff81626244: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81661d50)
Location: drivers/iommu/iommu.c:1399
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff81661d50-ffffffff81661dc3: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81680410)
Location: drivers/iommu/iommu.c:1475
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff81680410-ffffffff81680483: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b6a90)
Location: drivers/iommu/iommu.c:1692
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff816b6a90-ffffffff816b6b04: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816da4f0)
Location: drivers/iommu/iommu.c:1748
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff816da4f0-ffffffff816da564: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178eae8)
Location: drivers/iommu/iommu.c:2061
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bacf8)
Location: drivers/iommu/iommu.c:2271
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179e348)
Location: drivers/iommu/iommu.c:2302
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81827418)
Location: drivers/iommu/iommu.c:2323
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81966da8)
Location: drivers/iommu/iommu.c:2084
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad0850)
Location: drivers/iommu/iommu.c:2122
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff81ad0850-ffffffff81ad0902: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1eaf0)
Location: drivers/iommu/iommu.c:2083
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b74d10)
Location: drivers/iommu/iommu.c:2342
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff81b74d10-ffffffff81b74da0: __iommu_attach_group (STB_LOCAL)
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
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c5d28)
Location: drivers/iommu/iommu.c:1748
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffff8000108c5d28-ffff8000108c5dbc: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bd340)
Location: drivers/iommu/iommu.c:1748
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
c09bd340-c09bd3b8: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096c030)
Location: drivers/iommu/iommu.c:1748
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
c00000000096c030-c00000000096c100: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169ff40)
Location: drivers/iommu/iommu.c:1748
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff8169ff40-ffffffff8169ffb4: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167d930)
Location: drivers/iommu/iommu.c:1748
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff8167d930-ffffffff8167d9a4: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ce1b0)
Location: drivers/iommu/iommu.c:1748
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff816ce1b0-ffffffff816ce224: __iommu_attach_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __iommu_attach_group(struct iommu_domain *domain, struct iommu_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8700)
Location: drivers/iommu/iommu.c:1748
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_attach_group
  - drivers/iommu/iommu.c:iommu_attach_device
```
**Symbols:**

```
ffffffff816e8700-ffffffff816e8774: __iommu_attach_group (STB_LOCAL)
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
