# Function: <code>register_shrinker_prepared</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81208280)
Location: mm/vmscan.c:325
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff81208280-ffffffff812082c9: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121aed0)
Location: mm/vmscan.c:411
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff8121aed0-ffffffff8121af41: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122ab60)
Location: mm/vmscan.c:423
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff8122ab60-ffffffff8122abda: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81238a30)
Location: mm/vmscan.c:421
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff81238a30-ffffffff81238aaa: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81267315)
Location: mm/vmscan.c:378
Inline: True
Inline callers:
  - mm/vmscan.c:register_shrinker
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff812673c0-ffffffff8126742e: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81271d65)
Location: mm/vmscan.c:371
Inline: True
Inline callers:
  - mm/vmscan.c:register_shrinker
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff81271e10-ffffffff81271e7e: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8127708b)
Location: mm/vmscan.c:605
Inline: True
Inline callers:
  - mm/vmscan.c:register_shrinker
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff81277130-ffffffff81277180: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b49cb)
Location: mm/vmscan.c:651
Inline: True
Inline callers:
  - mm/vmscan.c:register_shrinker
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff812b4a70-ffffffff812b4ac0: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8131098b)
Location: mm/vmscan.c:648
Inline: True
Inline callers:
  - mm/vmscan.c:register_shrinker
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff81310a60-ffffffff81310aba: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8137e2fb)
Location: mm/vmscan.c:693
Inline: True
Inline callers:
  - mm/vmscan.c:register_shrinker
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff81383f00-ffffffff81383f5a: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813afd2b)
Location: mm/vmscan.c:745
Inline: True
Inline callers:
  - mm/vmscan.c:register_shrinker
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff813b59b0-ffffffff813b5a0a: register_shrinker_prepared (STB_GLOBAL)
```
</details>
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
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c97e8)
Location: mm/vmscan.c:421
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffff8000102c97e8-ffff8000102c9868: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f3798)
Location: mm/vmscan.c:421
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
c04f3798-c04f380c: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000385db0)
Location: mm/vmscan.c:421
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
c000000000385db0-c000000000385e78: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e8bce)
Location: mm/vmscan.c:421
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffe0001e8bce-ffffffe0001e8c4a: register_shrinker_prepared (STB_GLOBAL)
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
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81231080)
Location: mm/vmscan.c:421
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff81231080-ffffffff812310fa: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81224140)
Location: mm/vmscan.c:421
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff81224140-ffffffff812241ba: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122ee20)
Location: mm/vmscan.c:421
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff8122ee20-ffffffff8122ee9a: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void register_shrinker_prepared(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123e230)
Location: mm/vmscan.c:421
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff8123e230-ffffffff8123e2aa: register_shrinker_prepared (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
