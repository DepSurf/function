# Function: <code>__devm_ioremap</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814d0110)
Location: lib/devres.c:24
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
```
**Symbols:**

```
ffffffff814d0110-ffffffff814d01b1: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814e4a40)
Location: lib/devres.c:25
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
```
**Symbols:**

```
ffffffff814e4a40-ffffffff814e4ae1: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815113f0)
Location: lib/devres.c:26
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_uc
```
**Symbols:**

```
ffffffff815113f0-ffffffff815114b6: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81531e60)
Location: lib/devres.c:26
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_uc
```
**Symbols:**

```
ffffffff81531e60-ffffffff81531f26: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81596ab0)
Location: lib/devres.c:25
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
```
**Symbols:**

```
ffffffff81596390-ffffffff8159643e: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815b2564)
Location: lib/devres.c:25
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
```
**Symbols:**

```
ffffffff815b1e20-ffffffff815b1ece: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815bd270)
Location: lib/devres.c:26
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_np
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
```
**Symbols:**

```
ffffffff815bcc30-ffffffff815bcce7: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81624600)
Location: lib/devres.c:26
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_np
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
```
**Symbols:**

```
ffffffff81623ef0-ffffffff81623fae: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff816f4ca0)
Location: lib/devres.c:26
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_np
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
```
**Symbols:**

```
ffffffff816f42f0-ffffffff816f43c5: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff817e7076)
Location: lib/devres.c:26
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
```
**Symbols:**

```
ffffffff817e6380-ffffffff817e6456: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81827076)
Location: lib/devres.c:26
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
```
**Symbols:**

```
ffffffff81826350-ffffffff81826432: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81878a86)
Location: lib/devres.c:26
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_uc
  - lib/devres.c:devm_ioremap
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
```
**Symbols:**

```
ffffffff81877d60-ffffffff81877e42: __devm_ioremap (STB_LOCAL)
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
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffff80001063dd00)
Location: lib/devres.c:26
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_uc
```
**Symbols:**

```
ffff80001063dd00-ffff80001063df6c: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (c07e3b34)
Location: lib/devres.c:26
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_uc
```
**Symbols:**

```
c07e3b34-c07e3be8: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (c0000000007e7570)
Location: lib/devres.c:26
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_uc
```
**Symbols:**

```
c0000000007e7570-c0000000007e7698: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffe00046b3f2)
Location: lib/devres.c:26
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_uc
```
**Symbols:**

```
ffffffe00046b3f2-ffffffe00046b47c: __devm_ioremap (STB_LOCAL)
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
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8152a440)
Location: lib/devres.c:26
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_uc
```
**Symbols:**

```
ffffffff8152a440-ffffffff8152a506: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8151a720)
Location: lib/devres.c:26
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_uc
```
**Symbols:**

```
ffffffff8151a720-ffffffff8151a7e6: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815264d0)
Location: lib/devres.c:26
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_uc
```
**Symbols:**

```
ffffffff815264d0-ffffffff81526596: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8153fe50)
Location: lib/devres.c:26
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource
  - lib/devres.c:devm_ioremap_wc
  - lib/devres.c:devm_ioremap_nocache
  - lib/devres.c:devm_ioremap_uc
```
**Symbols:**

```
ffffffff8153fe50-ffffffff8153ff16: __devm_ioremap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
