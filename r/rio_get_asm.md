# Function: <code>rio_get_asm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81459030)
Location: drivers/rapidio/rio.c:1127
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff81459030-ffffffff81459142: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814a6af0)
Location: drivers/rapidio/rio.c:1442
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff814a6af0-ffffffff814a6bd7: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814c8c00)
Location: drivers/rapidio/rio.c:1442
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff814c8c00-ffffffff814c8ce7: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814d49d0)
Location: drivers/rapidio/rio.c:1439
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff814d49d0-ffffffff814d4ab6: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81514e80)
Location: drivers/rapidio/rio.c:1439
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff81514e80-ffffffff81514f66: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8154c990)
Location: drivers/rapidio/rio.c:1436
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff8154c990-ffffffff8154ca76: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81563a00)
Location: drivers/rapidio/rio.c:1436
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff81563a00-ffffffff81563ae6: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1432
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff815946d0-ffffffff815946eb: rio_get_asm.cold (STB_LOCAL)
ffffffff81593da0-ffffffff81593e7d: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815b4ef0)
Location: drivers/rapidio/rio.c:1432
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff815b4ef0-ffffffff815b4fd4: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8165ded0)
Location: drivers/rapidio/rio.c:1432
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff8165ded0-ffffffff8165dfb4: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffff80001073d068)
Location: drivers/rapidio/rio.c:1432
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffff80001073d068-ffff80001073d1e4: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c08c0a0c)
Location: drivers/rapidio/rio.c:1432
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
c08c0a0c-c08c0b6c: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c000000000893cf0)
Location: drivers/rapidio/rio.c:1432
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
c000000000893cf0-c000000000893eac: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffe0004ecf92)
Location: drivers/rapidio/rio.c:1432
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffe0004ecf92-ffffffe0004ed0bc: rio_get_asm (STB_GLOBAL)
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
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815a9160)
Location: drivers/rapidio/rio.c:1432
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff815a9160-ffffffff815a9244: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81598300)
Location: drivers/rapidio/rio.c:1432
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff81598300-ffffffff815983e4: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815a96f0)
Location: drivers/rapidio/rio.c:1432
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff815a96f0-ffffffff815a97d4: rio_get_asm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rio_dev *rio_get_asm(u16 vid, u16 did, u16 asm_vid, u16 asm_did, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815c1a60)
Location: drivers/rapidio/rio.c:1432
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
**Symbols:**

```
ffffffff815c1a60-ffffffff815c1b42: rio_get_asm (STB_GLOBAL)
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
