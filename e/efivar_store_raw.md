# Function: <code>efivar_store_raw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff816d2e70)
Location: drivers/firmware/efi/efivars.c:256
Inline: False
```
**Symbols:**

```
ffffffff816d2e70-ffffffff816d3213: efivar_store_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81736560)
Location: drivers/firmware/efi/efivars.c:256
Inline: False
```
**Symbols:**

```
ffffffff81736560-ffffffff81736df3: efivar_store_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff817696f0)
Location: drivers/firmware/efi/efivars.c:256
Inline: False
```
**Symbols:**

```
ffffffff817696f0-ffffffff81769f97: efivar_store_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81788050)
Location: drivers/firmware/efi/efivars.c:256
Inline: False
```
**Symbols:**

```
ffffffff81788050-ffffffff81788348: efivar_store_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff817fe4f0)
Location: drivers/firmware/efi/efivars.c:256
Inline: False
```
**Symbols:**

```
ffffffff817fe4f0-ffffffff817fe7e5: efivar_store_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:256
Inline: False
```
**Symbols:**

```
ffffffff81847b00-ffffffff81847db9: efivar_store_raw (STB_LOCAL)
ffffffff81847fbd-ffffffff81847fef: efivar_store_raw.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:248
Inline: False
```
**Symbols:**

```
ffffffff81873d50-ffffffff81874004: efivar_store_raw (STB_LOCAL)
ffffffff81874208-ffffffff8187423a: efivar_store_raw.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:192
Inline: False
```
**Symbols:**

```
ffffffff818b7f50-ffffffff818b81f4: efivar_store_raw (STB_LOCAL)
ffffffff818b83fe-ffffffff818b84a8: efivar_store_raw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:201
Inline: False
```
**Symbols:**

```
ffffffff818ea940-ffffffff818eabf5: efivar_store_raw (STB_LOCAL)
ffffffff818eadff-ffffffff818eaea9: efivar_store_raw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:201
Inline: False
```
**Symbols:**

```
ffffffff819be080-ffffffff819be32d: efivar_store_raw (STB_LOCAL)
ffffffff819be54e-ffffffff819be5f8: efivar_store_raw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:199
Inline: False
```
**Symbols:**

```
ffffffff819bfd00-ffffffff819bffad: efivar_store_raw (STB_LOCAL)
ffffffff81c2bd36-ffffffff81c2bde0: efivar_store_raw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:199
Inline: False
```
**Symbols:**

```
ffffffff819a4400-ffffffff819a46b5: efivar_store_raw (STB_LOCAL)
ffffffff81c1e092-ffffffff81c1e13c: efivar_store_raw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:199
Inline: False
```
**Symbols:**

```
ffffffff81a516b0-ffffffff81a51965: efivar_store_raw (STB_LOCAL)
ffffffff81d2f57a-ffffffff81d2f624: efivar_store_raw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:199
Inline: False
```
**Symbols:**

```
ffffffff81bc0620-ffffffff81bc08b7: efivar_store_raw (STB_LOCAL)
ffffffff81efb869-ffffffff81efb8e1: efivar_store_raw.cold (STB_LOCAL)
```
</details>
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
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffff800010b5dd00)
Location: drivers/firmware/efi/efivars.c:201
Inline: False
```
**Symbols:**

```
ffff800010b5dd00-ffff800010b5df58: efivar_store_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (c0c3dabc)
Location: drivers/firmware/efi/efivars.c:201
Inline: False
```
**Symbols:**

```
c0c3dabc-c0c3dca8: efivar_store_raw (STB_LOCAL)
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
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:201
Inline: False
```
**Symbols:**

```
ffffffff8188d6c0-ffffffff8188d975: efivar_store_raw (STB_LOCAL)
ffffffff8188db7f-ffffffff8188dc29: efivar_store_raw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:201
Inline: False
```
**Symbols:**

```
ffffffff81845040-ffffffff818452f5: efivar_store_raw (STB_LOCAL)
ffffffff818454ff-ffffffff818455a9: efivar_store_raw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:201
Inline: False
```
**Symbols:**

```
ffffffff818df7a0-ffffffff818dfa55: efivar_store_raw (STB_LOCAL)
ffffffff818dfc5f-ffffffff818dfd09: efivar_store_raw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_store_raw(struct efivar_entry *entry, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:201
Inline: False
```
**Symbols:**

```
ffffffff818fc240-ffffffff818fc4f5: efivar_store_raw (STB_LOCAL)
ffffffff818fc6ff-ffffffff818fc7a9: efivar_store_raw.cold (STB_LOCAL)
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
