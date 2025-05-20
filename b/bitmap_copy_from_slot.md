# Function: <code>bitmap_copy_from_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bitmap_copy_from_slot(struct mddev *mddev, int slot, sector_t *low, sector_t *high, bool clear_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169f6d0)
Location: drivers/md/bitmap.c:1866
Inline: False
```
**Symbols:**

```
ffffffff8169f6d0-ffffffff8169f94f: bitmap_copy_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bitmap_copy_from_slot(struct mddev *mddev, int slot, sector_t *low, sector_t *high, bool clear_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81700ac0)
Location: drivers/md/bitmap.c:1898
Inline: False
```
**Symbols:**

```
ffffffff81700ac0-ffffffff81700d35: bitmap_copy_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bitmap_copy_from_slot(struct mddev *mddev, int slot, sector_t *low, sector_t *high, bool clear_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81732830)
Location: drivers/md/bitmap.c:1926
Inline: False
```
**Symbols:**

```
ffffffff81732830-ffffffff81732a94: bitmap_copy_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bitmap_copy_from_slot(struct mddev *mddev, int slot, sector_t *low, sector_t *high, bool clear_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8174b670)
Location: drivers/md/bitmap.c:1966
Inline: False
```
**Symbols:**

```
ffffffff8174b670-ffffffff8174b869: bitmap_copy_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bitmap_copy_from_slot(struct mddev *mddev, int slot, sector_t *low, sector_t *high, bool clear_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bd9d0)
Location: drivers/md/md-bitmap.c:1976
Inline: False
```
**Symbols:**

```
ffffffff817bd9d0-ffffffff817bdbbd: bitmap_copy_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int bitmap_copy_from_slot(struct mddev *mddev, int slot, sector_t *low, sector_t *high, bool clear_bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1976
Inline: False
```
**Symbols:**

```
ffffffff818061e1-ffffffff818061ff: bitmap_copy_from_slot.cold.33 (STB_LOCAL)
ffffffff818059c0-ffffffff81805b99: bitmap_copy_from_slot (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
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
</ul>
