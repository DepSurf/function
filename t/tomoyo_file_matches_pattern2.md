# Function: <code>tomoyo_file_matches_pattern2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81373670)
Location: security/tomoyo/util.c:682
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
```
**Symbols:**

```
ffffffff81373670-ffffffff813739b9: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813a9a90)
Location: security/tomoyo/util.c:682
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff813a9a90-ffffffff813a9de0: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813c0600)
Location: security/tomoyo/util.c:682
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff813c0600-ffffffff813c0952: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813d6f70)
Location: security/tomoyo/util.c:684
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff813d6f70-ffffffff813d72fe: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813fd4a0)
Location: security/tomoyo/util.c:664
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff813fd4a0-ffffffff813fd834: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff8142e91e)
Location: security/tomoyo/util.c:664
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
```
**Symbols:**

```
ffffffff8142e530-ffffffff8142e8c6: tomoyo_file_matches_pattern2.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff8144b32e)
Location: security/tomoyo/util.c:664
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
```
**Symbols:**

```
ffffffff8144af00-ffffffff8144b2de: tomoyo_file_matches_pattern2.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81478a40)
Location: security/tomoyo/util.c:675
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff81478a40-ffffffff81478df9: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81492760)
Location: security/tomoyo/util.c:676
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff81492760-ffffffff81492afb: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814e9d40)
Location: security/tomoyo/util.c:676
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff814e9d40-ffffffff814ea0f3: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81507100)
Location: security/tomoyo/util.c:698
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff81507100-ffffffff815074d2: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8150dc80)
Location: security/tomoyo/util.c:698
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff8150dc80-ffffffff8150e052: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8156b7d0)
Location: security/tomoyo/util.c:698
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff8156b7d0-ffffffff8156bba2: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816079b0)
Location: security/tomoyo/util.c:698
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff816079b0-ffffffff81607d91: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816b9150)
Location: security/tomoyo/util.c:698
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff816b9150-ffffffff816b9530: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816f1b00)
Location: security/tomoyo/util.c:698
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff816f1b00-ffffffff816f1ed0: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8172e8c0)
Location: security/tomoyo/util.c:698
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff8172e8c0-ffffffff8172ec90: tomoyo_file_matches_pattern2 (STB_LOCAL)
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
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffff800010587650)
Location: security/tomoyo/util.c:676
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffff800010587650-ffff800010587a80: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0738b80)
Location: security/tomoyo/util.c:676
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
c0738b80-c0738fcc: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0000000006f75f0)
Location: security/tomoyo/util.c:676
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
c0000000006f75f0-c0000000006f7c10: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffe0003d69fc)
Location: security/tomoyo/util.c:676
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffe0003d69fc-ffffffe0003d6d40: tomoyo_file_matches_pattern2 (STB_LOCAL)
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
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8148ad40)
Location: security/tomoyo/util.c:676
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff8148ad40-ffffffff8148b0db: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8147b760)
Location: security/tomoyo/util.c:676
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff8147b760-ffffffff8147bafb: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81486de0)
Location: security/tomoyo/util.c:676
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff81486de0-ffffffff8148717b: tomoyo_file_matches_pattern2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tomoyo_file_matches_pattern2(const char *filename, const char *filename_end, const char *pattern, const char *pattern_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8149e920)
Location: security/tomoyo/util.c:676
Inline: False
Direct callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
**Symbols:**

```
ffffffff8149e920-ffffffff8149ecbb: tomoyo_file_matches_pattern2 (STB_LOCAL)
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
