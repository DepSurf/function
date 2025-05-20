# Function: <code>rio_mport_chk_dev_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81458db0)
Location: drivers/rapidio/rio.c:704
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff81458db0-ffffffff81458e32: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814a6940)
Location: drivers/rapidio/rio.c:1005
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff814a6940-ffffffff814a69c2: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814c8a50)
Location: drivers/rapidio/rio.c:1005
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff814c8a50-ffffffff814c8ad2: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814d4820)
Location: drivers/rapidio/rio.c:1002
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff814d4820-ffffffff814d48a2: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81514cd0)
Location: drivers/rapidio/rio.c:1002
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff81514cd0-ffffffff81514d52: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8154bd45)
Location: drivers/rapidio/rio.c:997
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff8154acf0-ffffffff8154ad72: rio_mport_chk_dev_access.part.13 (STB_LOCAL)
ffffffff8154ad80-ffffffff8154ad96: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815630d5)
Location: drivers/rapidio/rio.c:997
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff81562450-ffffffff815624d2: rio_mport_chk_dev_access.part.13 (STB_LOCAL)
ffffffff815624e0-ffffffff815624f6: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81592220)
Location: drivers/rapidio/rio.c:993
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff81592220-ffffffff815922a2: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815b34a0)
Location: drivers/rapidio/rio.c:993
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff815b34a0-ffffffff815b3522: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8165ef2b)
Location: drivers/rapidio/rio.c:993
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff8165caa0-ffffffff8165cb22: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff816802db)
Location: drivers/rapidio/rio.c:993
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff8167df80-ffffffff8167e002: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81662691)
Location: drivers/rapidio/rio.c:993
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff81660e00-ffffffff81660e82: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff816d54c1)
Location: drivers/rapidio/rio.c:993
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff816d3b70-ffffffff816d3bf2: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff817ff702)
Location: drivers/rapidio/rio.c:993
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff817fd400-ffffffff817fd498: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8192ca63)
Location: drivers/rapidio/rio.c:993
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff8192a440-ffffffff8192a4d8: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81970cf7)
Location: drivers/rapidio/rio.c:993
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff8196e6b0-ffffffff8196e748: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff819bad67)
Location: drivers/rapidio/rio.c:993
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff819b85a0-ffffffff819b8638: rio_mport_chk_dev_access (STB_GLOBAL)
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
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffff80001073ae70)
Location: drivers/rapidio/rio.c:993
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffff80001073ae70-ffff80001073af34: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c08c0614)
Location: drivers/rapidio/rio.c:993
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
c08c0614-c08c06c4: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c000000000893a50)
Location: drivers/rapidio/rio.c:993
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
c000000000893a50-c000000000893b50: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffe0004eb452)
Location: drivers/rapidio/rio.c:993
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffe0004eb452-ffffffe0004eb4b2: rio_mport_chk_dev_access (STB_GLOBAL)
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
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815a7710)
Location: drivers/rapidio/rio.c:993
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff815a7710-ffffffff815a7792: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815968b0)
Location: drivers/rapidio/rio.c:993
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff815968b0-ffffffff81596932: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815a7ca0)
Location: drivers/rapidio/rio.c:993
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff815a7ca0-ffffffff815a7d22: rio_mport_chk_dev_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rio_mport_chk_dev_access(struct rio_mport *mport, u16 destid, u8 hopcount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815c18b0)
Location: drivers/rapidio/rio.c:993
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff815c18b0-ffffffff815c1932: rio_mport_chk_dev_access (STB_GLOBAL)
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
