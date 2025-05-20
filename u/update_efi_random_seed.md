# Function: <code>update_efi_random_seed</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81766ad0)
Location: drivers/firmware/efi/efi.c:857
Inline: True
```
**Symbols:**

```
ffffffff81766ad0-ffffffff81766b6a: update_efi_random_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81785400)
Location: drivers/firmware/efi/efi.c:859
Inline: True
```
**Symbols:**

```
ffffffff81785400-ffffffff8178549c: update_efi_random_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff817fb770)
Location: drivers/firmware/efi/efi.c:919
Inline: True
```
**Symbols:**

```
ffffffff817fb770-ffffffff817fb80c: update_efi_random_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:994
Inline: True
```
**Symbols:**

```
ffffffff81844ee0-ffffffff81844f76: update_efi_random_seed (STB_LOCAL)
ffffffff81845161-ffffffff81845172: update_efi_random_seed.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81870f11)
Location: drivers/firmware/efi/efi.c:1112
Inline: True
```
**Symbols:**

```
ffffffff81870f00-ffffffff81870f96: update_efi_random_seed (STB_LOCAL)
ffffffff81871281-ffffffff81871292: update_efi_random_seed.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818b51e1)
Location: drivers/firmware/efi/efi.c:1124
Inline: True
```
**Symbols:**

```
ffffffff818b51d0-ffffffff818b5271: update_efi_random_seed (STB_LOCAL)
ffffffff818b54f7-ffffffff818b5508: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818e7b81)
Location: drivers/firmware/efi/efi.c:1124
Inline: True
```
**Symbols:**

```
ffffffff818e7b70-ffffffff818e7c11: update_efi_random_seed (STB_LOCAL)
ffffffff818e7e5a-ffffffff818e7e6b: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819bae10)
Location: drivers/firmware/efi/efi.c:1038
Inline: True
```
**Symbols:**

```
ffffffff819bad80-ffffffff819bae0f: update_efi_random_seed.part.0 (STB_LOCAL)
ffffffff819bb16b-ffffffff819bb17c: update_efi_random_seed.part.0.cold (STB_LOCAL)
ffffffff819bae10-ffffffff819bae2e: update_efi_random_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819bd070)
Location: drivers/firmware/efi/efi.c:1047
Inline: True
```
**Symbols:**

```
ffffffff819bcfe0-ffffffff819bd06f: update_efi_random_seed.part.0 (STB_LOCAL)
ffffffff81c2b6bc-ffffffff81c2b6cd: update_efi_random_seed.part.0.cold (STB_LOCAL)
ffffffff819bd070-ffffffff819bd08e: update_efi_random_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819a1791)
Location: drivers/firmware/efi/efi.c:1058
Inline: True
```
**Symbols:**

```
ffffffff819a1780-ffffffff819a181d: update_efi_random_seed (STB_LOCAL)
ffffffff81c1db55-ffffffff81c1db66: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81a4e74c)
Location: drivers/firmware/efi/efi.c:1065
Inline: True
```
**Symbols:**

```
ffffffff81a4e720-ffffffff81a4e7c9: update_efi_random_seed (STB_LOCAL)
ffffffff81d2efab-ffffffff81d2efd0: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81bbd356)
Location: drivers/firmware/efi/efi.c:1079
Inline: True
```
**Symbols:**

```
ffffffff81bbd320-ffffffff81bbd3da: update_efi_random_seed (STB_LOCAL)
ffffffff81efb45b-ffffffff81efb480: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81d62fa6)
Location: drivers/firmware/efi/efi.c:1106
Inline: True
```
**Symbols:**

```
ffffffff81d62f70-ffffffff81d63030: update_efi_random_seed (STB_LOCAL)
ffffffff820a9de7-ffffffff820a9dfb: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81dce076)
Location: drivers/firmware/efi/efi.c:1173
Inline: True
```
**Symbols:**

```
ffffffff81dce040-ffffffff81dce100: update_efi_random_seed (STB_LOCAL)
ffffffff8212b195-ffffffff8212b1a9: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81e86c46)
Location: drivers/firmware/efi/efi.c:1210
Inline: True
```
**Symbols:**

```
ffffffff81e86c10-ffffffff81e86cd0: update_efi_random_seed (STB_LOCAL)
ffffffff8220cf5e-ffffffff8220cf72: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffff800010b5abf8)
Location: drivers/firmware/efi/efi.c:1124
Inline: True
```
**Symbols:**

```
ffff800010b5abf8-ffff800010b5acbc: update_efi_random_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (c0c3b79c)
Location: drivers/firmware/efi/efi.c:1124
Inline: True
```
**Symbols:**

```
c0c3b79c-c0c3b84c: update_efi_random_seed (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8188a901)
Location: drivers/firmware/efi/efi.c:1124
Inline: True
```
**Symbols:**

```
ffffffff8188a8f0-ffffffff8188a991: update_efi_random_seed (STB_LOCAL)
ffffffff8188abda-ffffffff8188abeb: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81842281)
Location: drivers/firmware/efi/efi.c:1124
Inline: True
```
**Symbols:**

```
ffffffff81842270-ffffffff81842311: update_efi_random_seed (STB_LOCAL)
ffffffff8184255a-ffffffff8184256b: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818dc9e1)
Location: drivers/firmware/efi/efi.c:1124
Inline: True
```
**Symbols:**

```
ffffffff818dc9d0-ffffffff818dca71: update_efi_random_seed (STB_LOCAL)
ffffffff818dccba-ffffffff818dcccb: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int update_efi_random_seed(struct notifier_block *nb, long unsigned int code, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818f94f1)
Location: drivers/firmware/efi/efi.c:1124
Inline: True
```
**Symbols:**

```
ffffffff818f94e0-ffffffff818f9581: update_efi_random_seed (STB_LOCAL)
ffffffff818f97ca-ffffffff818f97db: update_efi_random_seed.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
