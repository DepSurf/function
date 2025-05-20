# Function: <code>kstrtobool_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81449640)
Location: lib/kstrtox.c:375
Inline: False
```
**Symbols:**

```
ffffffff81449640-ffffffff814496c8: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81468030)
Location: lib/kstrtox.c:371
Inline: False
```
**Symbols:**

```
ffffffff81468030-ffffffff814680b8: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8146d740)
Location: lib/kstrtox.c:373
Inline: False
```
**Symbols:**

```
ffffffff8146d740-ffffffff8146d7c8: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81499a70)
Location: lib/kstrtox.c:374
Inline: False
```
**Symbols:**

```
ffffffff81499a70-ffffffff81499af8: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814ced20)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
ffffffff814ced20-ffffffff814ceda8: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814e3630)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
ffffffff814e3630-ffffffff814e36b8: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8150fa10)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
ffffffff8150fa10-ffffffff8150fa98: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152d910)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
ffffffff8152d910-ffffffff8152d998: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81591620)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff81591620-ffffffff81591732: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815ae160)
Location: lib/kstrtox.c:371
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff815ae160-ffffffff815ae272: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815b9750)
Location: lib/kstrtox.c:378
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff815b9750-ffffffff815b9862: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81620070)
Location: lib/kstrtox.c:379
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff81620070-ffffffff816201a0: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff816ed9e0)
Location: lib/kstrtox.c:395
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - fs/debugfs/file.c:debugfs_write_file_bool
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff816ed9e0-ffffffff816eda92: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff817de400)
Location: lib/kstrtox.c:395
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:monitor_enable_write_data
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
  - fs/debugfs/file.c:debugfs_write_file_bool
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff817de400-ffffffff817de4b2: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8181dbe0)
Location: lib/kstrtox.c:395
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:monitor_enable_write_data
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
  - fs/debugfs/file.c:debugfs_write_file_bool
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff8181dbe0-ffffffff8181dc92: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81863a50)
Location: lib/kstrtox.c:395
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:monitor_enable_write_data
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
  - fs/debugfs/file.c:debugfs_write_file_bool
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff81863a50-ffffffff81863b02: kstrtobool_from_user (STB_GLOBAL)
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
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffff800010639cc0)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
ffff800010639cc0-ffff800010639d5c: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c07df5a4)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
c07df5a4-c07df690: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c0000000007e0890)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
c0000000007e0890-c0000000007e0960: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffe0004665f8)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
ffffffe0004665f8-ffffffe000466660: kstrtobool_from_user (STB_GLOBAL)
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
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81525ef0)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
ffffffff81525ef0-ffffffff81525f78: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815161d0)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
ffffffff815161d0-ffffffff81516258: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81521f80)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
ffffffff81521f80-ffffffff81522008: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kstrtobool_from_user(const char *s, size_t count, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8153b900)
Location: lib/kstrtox.c:374
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_write_file_bool
```
**Symbols:**

```
ffffffff8153b900-ffffffff8153b988: kstrtobool_from_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
