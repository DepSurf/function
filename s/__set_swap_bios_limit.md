# Function: <code>__set_swap_bios_limit</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __set_swap_bios_limit(struct mapped_device *md, int latch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197bbf0)
Location: drivers/md/dm.c:1275
Inline: False
```
**Symbols:**

```
ffffffff8197bbf0-ffffffff8197bc86: __set_swap_bios_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __set_swap_bios_limit(struct mapped_device *md, int latch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8195fd00)
Location: drivers/md/dm.c:1283
Inline: False
```
**Symbols:**

```
ffffffff8195fd00-ffffffff8195fd96: __set_swap_bios_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __set_swap_bios_limit(struct mapped_device *md, int latch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a07cb0)
Location: drivers/md/dm.c:1170
Inline: False
```
**Symbols:**

```
ffffffff81a07cb0-ffffffff81a07d46: __set_swap_bios_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __set_swap_bios_limit(struct mapped_device *md, int latch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b70410)
Location: drivers/md/dm.c:1297
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff81b70410-ffffffff81b704b0: __set_swap_bios_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __set_swap_bios_limit(struct mapped_device *md, int latch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0cde0)
Location: drivers/md/dm.c:1372
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff81d0cde0-ffffffff81d0ce80: __set_swap_bios_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __set_swap_bios_limit(struct mapped_device *md, int latch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d75ba0)
Location: drivers/md/dm.c:1396
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff81d75ba0-ffffffff81d75c40: __set_swap_bios_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __set_swap_bios_limit(struct mapped_device *md, int latch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2cca0)
Location: drivers/md/dm.c:1382
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff81e2cca0-ffffffff81e2cd40: __set_swap_bios_limit (STB_LOCAL)
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
