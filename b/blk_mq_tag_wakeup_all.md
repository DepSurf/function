# Function: <code>blk_mq_tag_wakeup_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff813c7530)
Location: block/blk-mq-tag.c:73
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff813c7530-ffffffff813c75bc: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8140b760)
Location: block/blk-mq-tag.c:73
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
**Symbols:**

```
ffffffff8140b760-ffffffff8140b7f2: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814262dd)
Location: block/blk-mq-tag.c:39
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff81425e20-ffffffff81425e4e: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81433a1e)
Location: block/blk-mq-tag.c:39
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff814339d0-ffffffff814339fe: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8145f6de)
Location: block/blk-mq-tag.c:39
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff8145f690-ffffffff8145f6be: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81492fbf)
Location: block/blk-mq-tag.c:42
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff81492f60-ffffffff81492f93: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814acedf)
Location: block/blk-mq-tag.c:42
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff814ace80-ffffffff814aceb3: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814db1ee)
Location: block/blk-mq-tag.c:43
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff814db190-ffffffff814db1c3: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814f461e)
Location: block/blk-mq-tag.c:44
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff814f45c0-ffffffff814f45f3: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81554c9e)
Location: block/blk-mq-tag.c:36
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff81554c40-ffffffff81554c73: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81571448)
Location: block/blk-mq-tag.c:45
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff815713d0-ffffffff81571403: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81579478)
Location: block/blk-mq-tag.c:45
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff81579400-ffffffff81579433: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815de6b8)
Location: block/blk-mq-tag.c:46
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff815de640-ffffffff815de673: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8168c866)
Location: block/blk-mq-tag.c:68
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff8168c7d0-ffffffff8168c813: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8174b036)
Location: block/blk-mq-tag.c:64
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff8174af90-ffffffff8174afd3: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8178775e)
Location: block/blk-mq-tag.c:69
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff817876a0-ffffffff817876e3: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817c9e2b)
Location: block/blk-mq-tag.c:69
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff817c9d70-ffffffff817c9db3: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffff8000105f437c)
Location: block/blk-mq-tag.c:44
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffff8000105f42b0-ffff8000105f42f8: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c07a0000)
Location: block/blk-mq-tag.c:44
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
c079ff7c-c079ffb4: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c00000000078bb8c)
Location: block/blk-mq-tag.c:44
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
c00000000078baa0-c00000000078bb24: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffe0004323f6)
Location: block/blk-mq-tag.c:44
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffe000432376-ffffffe0004323c4: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814ecbfe)
Location: block/blk-mq-tag.c:44
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff814ecba0-ffffffff814ecbd3: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814dd14e)
Location: block/blk-mq-tag.c:44
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff814dd0f0-ffffffff814dd123: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814e8c8e)
Location: block/blk-mq-tag.c:44
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff814e8c30-ffffffff814e8c63: blk_mq_tag_wakeup_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tag_wakeup_all(struct blk_mq_tags *tags, bool include_reserve);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81501c2e)
Location: block/blk-mq-tag.c:44
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
Direct callers:
  - block/blk-mq.c:blk_mq_wake_waiters
```
**Symbols:**

```
ffffffff81501bd0-ffffffff81501c03: blk_mq_tag_wakeup_all (STB_GLOBAL)
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
