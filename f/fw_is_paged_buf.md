# Function: <code>fw_is_paged_buf</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool fw_is_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d533b)
Location: drivers/base/firmware_loader/main.c:273
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:__free_fw_priv
```
**Symbols:**

```
ffffffff817d5950-ffffffff817d595f: fw_is_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool fw_is_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817e9c0b)
Location: drivers/base/firmware_loader/main.c:294
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:__free_fw_priv
```
**Symbols:**

```
ffffffff817ea360-ffffffff817ea36f: fw_is_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool fw_is_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ce33b)
Location: drivers/base/firmware_loader/main.c:295
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:__free_fw_priv
```
**Symbols:**

```
ffffffff817cea60-ffffffff817cea6f: fw_is_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fw_is_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81858bdb)
Location: drivers/base/firmware_loader/main.c:296
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:__free_fw_priv
```
**Symbols:**

```
ffffffff81d04253-ffffffff81d04273: fw_is_paged_buf.cold (STB_LOCAL)
ffffffff81859160-ffffffff81859175: fw_is_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fw_is_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199ec25)
Location: drivers/base/firmware_loader/main.c:233
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:__free_fw_priv
```
**Symbols:**

```
ffffffff81eccb76-ffffffff81eccba0: fw_is_paged_buf.cold (STB_LOCAL)
ffffffff8199fc50-ffffffff8199fc6f: fw_is_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fw_is_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b10625)
Location: drivers/base/firmware_loader/main.c:233
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:__free_fw_priv
```
**Symbols:**

```
ffffffff82098b3e-ffffffff82098b68: fw_is_paged_buf.cold (STB_LOCAL)
ffffffff81b11720-ffffffff81b1173f: fw_is_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fw_is_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5e845)
Location: drivers/base/firmware_loader/main.c:233
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:__free_fw_priv
```
**Symbols:**

```
ffffffff82119af5-ffffffff82119b1f: fw_is_paged_buf.cold (STB_LOCAL)
ffffffff81b5f9b0-ffffffff81b5f9cf: fw_is_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fw_is_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb21b5)
Location: drivers/base/firmware_loader/main.c:234
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:__free_fw_priv
```
**Symbols:**

```
ffffffff821f79cd-ffffffff821f79f7: fw_is_paged_buf.cold (STB_LOCAL)
ffffffff81bb33c0-ffffffff81bb33df: fw_is_paged_buf (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
