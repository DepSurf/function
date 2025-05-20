# Function: <code>store_cache_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103eaf0)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff8103eaf0-ffffffff8103ec72: store_cache_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e920)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff8103e920-ffffffff8103eaa7: store_cache_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e2a0)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff8103e2a0-ffffffff8103e430: store_cache_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103c290)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:430
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff8103c290-ffffffff8103c3f3: store_cache_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103eea0)
Location: arch/x86/kernel/cpu/intel_cacheinfo.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff8103eea0-ffffffff8103f003: store_cache_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040490)
Location: arch/x86/kernel/cpu/cacheinfo.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81040490-ffffffff810405fa: store_cache_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81041a50)
Location: arch/x86/kernel/cpu/cacheinfo.c:434
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81041a50-ffffffff81041bba: store_cache_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81043f00-ffffffff81044061: store_cache_disable (STB_LOCAL)
ffffffff8104538a-ffffffff810453a5: store_cache_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81044650-ffffffff810447b1: store_cache_disable (STB_LOCAL)
ffffffff81045ada-ffffffff81045af5: store_cache_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff810485b0-ffffffff8104872d: store_cache_disable (STB_LOCAL)
ffffffff810498fa-ffffffff81049915: store_cache_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81047aa0-ffffffff81047c1d: store_cache_disable (STB_LOCAL)
ffffffff81bd4ed3-ffffffff81bd4eee: store_cache_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81049560-ffffffff810496dd: store_cache_disable (STB_LOCAL)
ffffffff81bc7287-ffffffff81bc72a2: store_cache_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81050000-ffffffff8105019e: store_cache_disable (STB_LOCAL)
ffffffff81c9a8a7-ffffffff81c9a8c2: store_cache_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff8105b5b0-ffffffff8105b757: store_cache_disable (STB_LOCAL)
ffffffff81e49d77-ffffffff81e49d92: store_cache_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81069010)
Location: arch/x86/kernel/cpu/cacheinfo.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81069010-ffffffff810691d1: store_cache_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106ae10)
Location: arch/x86/kernel/cpu/cacheinfo.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff8106ae10-ffffffff8106afd1: store_cache_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81072210)
Location: arch/x86/kernel/cpu/cacheinfo.c:459
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81072210-ffffffff810723d1: store_cache_disable (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff810447d0-ffffffff81044931: store_cache_disable (STB_LOCAL)
ffffffff81045c5a-ffffffff81045c75: store_cache_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81033d50-ffffffff81033eb1: store_cache_disable (STB_LOCAL)
ffffffff8103506a-ffffffff81035085: store_cache_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81044610-ffffffff81044771: store_cache_disable (STB_LOCAL)
ffffffff81045a9a-ffffffff81045ab5: store_cache_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t store_cache_disable(struct cacheinfo *this_leaf, const char *buf, size_t count, unsigned int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_1_store
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable_0_store
```
**Symbols:**

```
ffffffff81045a10-ffffffff81045b71: store_cache_disable (STB_LOCAL)
ffffffff81046e9a-ffffffff81046eb5: store_cache_disable.cold (STB_LOCAL)
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
