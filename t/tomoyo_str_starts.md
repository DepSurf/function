# Function: <code>tomoyo_str_starts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81374270)
Location: security/tomoyo/util.c:392
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff81374270-ffffffff813742c0: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813aa670)
Location: security/tomoyo/util.c:392
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff813aa670-ffffffff813aa6c0: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813c11f0)
Location: security/tomoyo/util.c:392
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff813c11f0-ffffffff813c1240: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813d7b70)
Location: security/tomoyo/util.c:394
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff813d7b70-ffffffff813d7bc0: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813fdfc0)
Location: security/tomoyo/util.c:374
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff813fdfc0-ffffffff813fe010: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8142eea0)
Location: security/tomoyo/util.c:374
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff8142eea0-ffffffff8142eef0: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8144b8c0)
Location: security/tomoyo/util.c:374
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff8144b8c0-ffffffff8144b910: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81479620)
Location: security/tomoyo/util.c:382
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff81479620-ffffffff81479670: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81493320)
Location: security/tomoyo/util.c:382
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff81493320-ffffffff81493370: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814ea6e0)
Location: security/tomoyo/util.c:382
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff814ea6e0-ffffffff814ea730: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81507ac0)
Location: security/tomoyo/util.c:384
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff81507ac0-ffffffff81507b10: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8150e640)
Location: security/tomoyo/util.c:384
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff8150e640-ffffffff8150e690: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8156c190)
Location: security/tomoyo/util.c:384
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff8156c190-ffffffff8156c1e0: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81608480)
Location: security/tomoyo/util.c:384
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff81608480-ffffffff816084da: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816b9ca0)
Location: security/tomoyo/util.c:384
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff816b9ca0-ffffffff816b9cfa: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816f2640)
Location: security/tomoyo/util.c:384
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff816f2640-ffffffff816f269a: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8172f400)
Location: security/tomoyo/util.c:384
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_set_mode
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff8172f400-ffffffff8172f45a: tomoyo_str_starts (STB_GLOBAL)
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
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffff8000105884d0)
Location: security/tomoyo/util.c:382
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffff8000105884d0-ffff800010588544: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c07399e8)
Location: security/tomoyo/util.c:382
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
c07399e8-c0739a3c: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0000000006f8ab0)
Location: security/tomoyo/util.c:382
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
c0000000006f8ab0-c0000000006f8b60: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffe0003d7590)
Location: security/tomoyo/util.c:382
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffe0003d7590-ffffffe0003d75fa: tomoyo_str_starts (STB_GLOBAL)
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
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8148b900)
Location: security/tomoyo/util.c:382
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff8148b900-ffffffff8148b950: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8147c320)
Location: security/tomoyo/util.c:382
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff8147c320-ffffffff8147c370: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814879a0)
Location: security/tomoyo/util.c:382
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff814879a0-ffffffff814879f0: tomoyo_str_starts (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tomoyo_str_starts(char **src, const char *find);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8149f4e0)
Location: security/tomoyo/util.c:382
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_stat
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_write_exception
  - security/tomoyo/common.c:tomoyo_read_pid
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_domain2
  - security/tomoyo/common.c:tomoyo_write_task
  - security/tomoyo/common.c:tomoyo_write_profile
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff8149f4e0-ffffffff8149f530: tomoyo_str_starts (STB_GLOBAL)
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
