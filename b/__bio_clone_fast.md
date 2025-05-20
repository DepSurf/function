# Function: <code>__bio_clone_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b0810)
Location: block/bio.c:574
Inline: True
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__clone_and_map_simple_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff813b0810-ffffffff813b086a: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f6760)
Location: block/bio.c:573
Inline: True
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__clone_and_map_simple_bio
```
**Symbols:**

```
ffffffff813f6760-ffffffff813f67c0: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81410140)
Location: block/bio.c:577
Inline: True
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__clone_and_map_simple_bio
```
**Symbols:**

```
ffffffff81410140-ffffffff814101a0: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141db70)
Location: block/bio.c:591
Inline: True
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__clone_and_map_simple_bio
```
**Symbols:**

```
ffffffff8141db70-ffffffff8141dbd8: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81446610)
Location: block/bio.c:591
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__clone_and_map_simple_bio
```
**Symbols:**

```
ffffffff81446610-ffffffff8144668f: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479ae0)
Location: block/bio.c:592
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff81479ae0-ffffffff81479b5d: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814981e0)
Location: block/bio.c:593
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff814981e0-ffffffff814982ca: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6060)
Location: block/bio.c:573
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff814c6060-ffffffff814c6147: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de460)
Location: block/bio.c:625
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff814de460-ffffffff814de54a: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153df80)
Location: block/bio.c:672
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:clone_bio
```
**Symbols:**

```
ffffffff8153df80-ffffffff8153e069: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81559f70)
Location: block/bio.c:674
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:clone_bio
```
**Symbols:**

```
ffffffff81559f70-ffffffff8155a04e: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562880)
Location: block/bio.c:629
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff81562880-ffffffff81562968: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c65a0)
Location: block/bio.c:712
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff815c65a0-ffffffff815c6682: __bio_clone_fast (STB_GLOBAL)
```
</details>
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
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105db8b0)
Location: block/bio.c:625
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffff8000105db8b0-ffff8000105db990: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0788450)
Location: block/bio.c:625
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
c0788450-c0788538: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076b7d0)
Location: block/bio.c:625
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
c00000000076b7d0-c00000000076b8ec: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e4e8)
Location: block/bio.c:625
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffe00041e4e8-ffffffe00041e5ce: __bio_clone_fast (STB_GLOBAL)
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
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6a40)
Location: block/bio.c:625
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff814d6a40-ffffffff814d6b2a: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7400)
Location: block/bio.c:625
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff814c7400-ffffffff814c74ea: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2ad0)
Location: block/bio.c:625
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff814d2ad0-ffffffff814d2bba: __bio_clone_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bio_clone_fast(struct bio *bio, struct bio *bio_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb660)
Location: block/bio.c:625
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
**Symbols:**

```
ffffffff814eb660-ffffffff814eb740: __bio_clone_fast (STB_GLOBAL)
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
