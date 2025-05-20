# Function: <code>iommu_enable_command_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81532a36)
Location: drivers/iommu/amd_iommu_init.c:531
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81587304)
Location: drivers/iommu/amd_iommu_init.c:585
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815b49a7)
Location: drivers/iommu/amd_iommu_init.c:594
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca713)
Location: drivers/iommu/amd_iommu_init.c:603
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81631210)
Location: drivers/iommu/amd_iommu_init.c:632
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81631210-ffffffff8163126b: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166c0d0)
Location: drivers/iommu/amd_iommu_init.c:632
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8166c0d0-ffffffff8166c12b: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a8f0)
Location: drivers/iommu/amd_iommu_init.c:635
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8168a8f0-ffffffff8168a990: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c2320)
Location: drivers/iommu/amd_iommu_init.c:623
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816c2320-ffffffff816c23c3: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e5240)
Location: drivers/iommu/amd_iommu_init.c:624
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816e5240-ffffffff816e52e3: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179b6b0)
Location: drivers/iommu/amd/init.c:624
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8179b6b0-ffffffff8179b74f: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a9af0)
Location: drivers/iommu/amd/init.c:665
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff817a9af0-ffffffff817a9b8f: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178b820)
Location: drivers/iommu/amd/init.c:661
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8178b820-ffffffff8178b8bf: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff818126e0)
Location: drivers/iommu/amd/init.c:688
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff818126e0-ffffffff818127cd: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81953650)
Location: drivers/iommu/amd/init.c:692
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81953650-ffffffff8195374b: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab8ef0)
Location: drivers/iommu/amd/init.c:774
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81ab8ef0-ffffffff81ab8fee: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b05270)
Location: drivers/iommu/amd/init.c:809
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81b05270-ffffffff81b0536e: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b58c80)
Location: drivers/iommu/amd/init.c:822
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81b58c80-ffffffff81b58d7e: iommu_enable_command_buffer (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aad20)
Location: drivers/iommu/amd_iommu_init.c:624
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816aad20-ffffffff816aadc3: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81688680)
Location: drivers/iommu/amd_iommu_init.c:624
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81688680-ffffffff81688723: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8f00)
Location: drivers/iommu/amd_iommu_init.c:624
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816d8f00-ffffffff816d8fa3: iommu_enable_command_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_command_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f34b0)
Location: drivers/iommu/amd_iommu_init.c:624
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816f34b0-ffffffff816f3553: iommu_enable_command_buffer (STB_LOCAL)
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
