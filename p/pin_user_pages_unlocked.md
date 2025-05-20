# Function: <code>pin_user_pages_unlocked</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
long int pin_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128a260)
Location: mm/gup.c:3046
Inline: False
```
**Symbols:**

```
ffffffff8128a260-ffffffff8128a285: pin_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int pin_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81294010)
Location: mm/gup.c:2833
Inline: False
```
**Symbols:**

```
ffffffff81294010-ffffffff81294035: pin_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int pin_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812999a0)
Location: mm/gup.c:2899
Inline: False
```
**Symbols:**

```
ffffffff812999a0-ffffffff812999c5: pin_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int pin_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812da320)
Location: mm/gup.c:2994
Inline: False
```
**Symbols:**

```
ffffffff812da320-ffffffff812da345: pin_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int pin_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81339d00)
Location: mm/gup.c:3154
Inline: False
```
**Symbols:**

```
ffffffff81339d00-ffffffff81339d58: pin_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int pin_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b1ce0)
Location: mm/gup.c:3180
Inline: False
```
**Symbols:**

```
ffffffff813b1ce0-ffffffff813b1d38: pin_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int pin_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e6b50)
Location: mm/gup.c:3384
Inline: False
```
**Symbols:**

```
ffffffff813e6b50-ffffffff813e6c08: pin_user_pages_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int pin_user_pages_unlocked(long unsigned int start, long unsigned int nr_pages, struct page **pages, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff814117e0)
Location: mm/gup.c:3402
Inline: False
```
**Symbols:**

```
ffffffff814117e0-ffffffff81411898: pin_user_pages_unlocked (STB_GLOBAL)
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
