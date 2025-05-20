# Function: <code>nvmem_device_release</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886430)
Location: drivers/nvmem/core.c:707
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_put
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:devm_nvmem_device_release
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff81886430-ffffffff81886494: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d0b00)
Location: drivers/nvmem/core.c:453
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff818d0b00-ffffffff818d0b63: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81902f60)
Location: drivers/nvmem/core.c:450
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff81902f60-ffffffff81902fc3: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819da670)
Location: drivers/nvmem/core.c:691
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff819da670-ffffffff819da6f9: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9500)
Location: drivers/nvmem/core.c:866
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff819d9500-ffffffff819d9589: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bf7a0)
Location: drivers/nvmem/core.c:869
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff819bf7a0-ffffffff819bf829: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6edf0)
Location: drivers/nvmem/core.c:880
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff81a6edf0-ffffffff81a6ee79: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81bdfe60)
Location: drivers/nvmem/core.c:885
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff81bdfe60-ffffffff81bdfef7: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8b610)
Location: drivers/nvmem/core.c:883
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff81d8b610-ffffffff81d8b6a7: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81df9b90)
Location: drivers/nvmem/core.c:1032
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff81df9b90-ffffffff81df9c09: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb109a)
Location: drivers/nvmem/core.c:1043
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
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
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9ecb8)
Location: drivers/nvmem/core.c:450
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:nvmem_unregister
```
**Symbols:**

```
ffff800010b9ecb8-ffff800010b9ed28: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c80a84)
Location: drivers/nvmem/core.c:450
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:nvmem_unregister
```
**Symbols:**

```
c0c80a84-c0c80af0: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c71ec0)
Location: drivers/nvmem/core.c:450
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:nvmem_unregister
```
**Symbols:**

```
c000000000c71ec0-c000000000c71f9c: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000736fac)
Location: drivers/nvmem/core.c:450
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffe000736fac-ffffffe000737022: nvmem_device_release (STB_LOCAL)
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
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a2390)
Location: drivers/nvmem/core.c:450
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff818a2390-ffffffff818a23f3: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185db00)
Location: drivers/nvmem/core.c:450
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff8185db00-ffffffff8185db63: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f3980)
Location: drivers/nvmem/core.c:450
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff818f3980-ffffffff818f39e3: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nvmem_device_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81914a20)
Location: drivers/nvmem/core.c:450
Inline: False
Direct callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
**Symbols:**

```
ffffffff81914a20-ffffffff81914a83: nvmem_device_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
