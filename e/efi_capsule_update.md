# Function: <code>efi_capsule_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/capsule.c (ffffffff81735260)
Location: drivers/firmware/efi/capsule.c:217
Inline: False
```
**Symbols:**

```
ffffffff81735260-ffffffff817355f7: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/capsule.c (ffffffff817683e0)
Location: drivers/firmware/efi/capsule.c:217
Inline: False
```
**Symbols:**

```
ffffffff817683e0-ffffffff8176876d: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/capsule.c (ffffffff81786cc0)
Location: drivers/firmware/efi/capsule.c:217
Inline: False
```
**Symbols:**

```
ffffffff81786cc0-ffffffff81787012: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/capsule.c (ffffffff817fd150)
Location: drivers/firmware/efi/capsule.c:217
Inline: False
```
**Symbols:**

```
ffffffff817fd150-ffffffff817fd4a8: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:217
Inline: False
```
**Symbols:**

```
ffffffff81846ce8-ffffffff81846cfe: efi_capsule_update.cold.2 (STB_LOCAL)
ffffffff81846950-ffffffff81846cb1: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:217
Inline: False
```
**Symbols:**

```
ffffffff81872f43-ffffffff81872f59: efi_capsule_update.cold.2 (STB_LOCAL)
ffffffff81872bb0-ffffffff81872f11: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:215
Inline: False
```
**Symbols:**

```
ffffffff818b7113-ffffffff818b7142: efi_capsule_update.cold (STB_LOCAL)
ffffffff818b6d90-ffffffff818b70e8: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:215
Inline: False
```
**Symbols:**

```
ffffffff818e9a73-ffffffff818e9aa2: efi_capsule_update.cold (STB_LOCAL)
ffffffff818e96f0-ffffffff818e9a48: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:215
Inline: False
```
**Symbols:**

```
ffffffff819bd163-ffffffff819bd192: efi_capsule_update.cold (STB_LOCAL)
ffffffff819bce20-ffffffff819bd13f: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:216
Inline: False
```
**Symbols:**

```
ffffffff81c2bb0c-ffffffff81c2bb3b: efi_capsule_update.cold (STB_LOCAL)
ffffffff819bebe0-ffffffff819beef4: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:216
Inline: False
```
**Symbols:**

```
ffffffff81c1de8b-ffffffff81c1deba: efi_capsule_update.cold (STB_LOCAL)
ffffffff819a32d0-ffffffff819a35f3: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:216
Inline: False
```
**Symbols:**

```
ffffffff81d2f32f-ffffffff81d2f372: efi_capsule_update.cold (STB_LOCAL)
ffffffff81a50550-ffffffff81a50883: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:216
Inline: False
```
**Symbols:**

```
ffffffff81efb622-ffffffff81efb65e: efi_capsule_update.cold (STB_LOCAL)
ffffffff81bbf420-ffffffff81bbf76c: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:216
Inline: False
```
**Symbols:**

```
ffffffff820a9e4d-ffffffff820a9e62: efi_capsule_update.cold (STB_LOCAL)
ffffffff81d63c40-ffffffff81d63fb0: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:216
Inline: False
```
**Symbols:**

```
ffffffff8212b1fb-ffffffff8212b210: efi_capsule_update.cold (STB_LOCAL)
ffffffff81dced90-ffffffff81dcf100: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:216
Inline: False
```
**Symbols:**

```
ffffffff8220cfc4-ffffffff8220cfd9: efi_capsule_update.cold (STB_LOCAL)
ffffffff81e87ac0-ffffffff81e87e30: efi_capsule_update (STB_GLOBAL)
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
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/capsule.c (ffff800010b5ca70)
Location: drivers/firmware/efi/capsule.c:215
Inline: False
```
**Symbols:**

```
ffff800010b5ca70-ffff800010b5cd64: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/capsule.c (c0c3d604)
Location: drivers/firmware/efi/capsule.c:215
Inline: False
```
**Symbols:**

```
c0c3d604-c0c3d9c8: efi_capsule_update (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:215
Inline: False
```
**Symbols:**

```
ffffffff8188c7f3-ffffffff8188c822: efi_capsule_update.cold (STB_LOCAL)
ffffffff8188c470-ffffffff8188c7c8: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:215
Inline: False
```
**Symbols:**

```
ffffffff81844173-ffffffff818441a2: efi_capsule_update.cold (STB_LOCAL)
ffffffff81843df0-ffffffff81844148: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:215
Inline: False
```
**Symbols:**

```
ffffffff818de8d3-ffffffff818de902: efi_capsule_update.cold (STB_LOCAL)
ffffffff818de550-ffffffff818de8a8: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int efi_capsule_update(efi_capsule_header_t *capsule, phys_addr_t *pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/capsule.c (0)
Location: drivers/firmware/efi/capsule.c:215
Inline: False
```
**Symbols:**

```
ffffffff818fb373-ffffffff818fb3a2: efi_capsule_update.cold (STB_LOCAL)
ffffffff818fb060-ffffffff818fb347: efi_capsule_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct page **pages</code> ➡️ <code>phys_addr_t *pages</code>
</li>
</ul>
</details>
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
