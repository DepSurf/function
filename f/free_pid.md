# Function: <code>free_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109df50)
Location: kernel/pid.c:259
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff8109df50-ffffffff8109e087: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a15c0)
Location: kernel/pid.c:259
Inline: False
Direct callers:
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810a15c0-ffffffff810a16fa: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6680)
Location: kernel/pid.c:259
Inline: False
Direct callers:
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810a6680-ffffffff810a67ba: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3610)
Location: kernel/pid.c:258
Inline: False
Direct callers:
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810a3610-ffffffff810a372b: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9e40)
Location: kernel/pid.c:111
Inline: False
Direct callers:
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810a9e40-ffffffff810a9f19: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0a60)
Location: kernel/pid.c:123
Inline: False
Direct callers:
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810b0a60-ffffffff810b0b38: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b9b30)
Location: kernel/pid.c:123
Inline: False
Direct callers:
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810b9b30-ffffffff810b9c08: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/pid.c (0)
Location: kernel/pid.c:124
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810c0117-ffffffff810c012a: free_pid.cold (STB_LOCAL)
ffffffff810bfa40-ffffffff810bfb18: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5e10)
Location: kernel/pid.c:124
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810c5e10-ffffffff810c5ee8: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cdba0)
Location: kernel/pid.c:125
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810cdba0-ffffffff810cdc61: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8680)
Location: kernel/pid.c:126
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810c8680-ffffffff810c8740: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ca120)
Location: kernel/pid.c:126
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810ca120-ffffffff810ca1e0: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dcf10)
Location: kernel/pid.c:126
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810dcf10-ffffffff810dcfd0: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f67c0)
Location: kernel/pid.c:126
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810f67c0-ffffffff810f688a: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81118e80)
Location: kernel/pid.c:126
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff81118e80-ffffffff81118f4a: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126340)
Location: kernel/pid.c:129
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff81126340-ffffffff8112640a: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81130940)
Location: kernel/pid.c:129
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff81130940-ffffffff81130a0a: free_pid (STB_GLOBAL)
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
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff8000101243f0)
Location: kernel/pid.c:124
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffff8000101243f0-ffff80001012456c: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c03775e4)
Location: kernel/pid.c:124
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
c03775e4-c03776e0: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016e070)
Location: kernel/pid.c:124
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
c00000000016e070-c00000000016e1f8: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc4c6)
Location: kernel/pid.c:124
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffe0000dc4c6-ffffffe0000dc5d2: free_pid (STB_GLOBAL)
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
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c0190)
Location: kernel/pid.c:124
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810c0190-ffffffff810c0268: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae9a0)
Location: kernel/pid.c:124
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810ae9a0-ffffffff810aea78: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf6e0)
Location: kernel/pid.c:124
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810bf6e0-ffffffff810bf7b8: free_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7af0)
Location: kernel/pid.c:124
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/pid.c:__change_pid
```
**Symbols:**

```
ffffffff810c7af0-ffffffff810c7bc8: free_pid (STB_GLOBAL)
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
