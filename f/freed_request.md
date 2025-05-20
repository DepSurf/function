# Function: <code>freed_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void freed_request(struct request_list *rl, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5e20)
Location: block/blk-core.c:954
Inline: False
Direct callers:
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff813b5e20-ffffffff813b5e94: freed_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void freed_request(struct request_list *rl, int op, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fac70)
Location: block/blk-core.c:964
Inline: False
Direct callers:
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff813fac70-ffffffff813face3: freed_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void freed_request(struct request_list *rl, bool sync, req_flags_t rq_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814145d0)
Location: block/blk-core.c:966
Inline: False
Direct callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff814145d0-ffffffff8141462e: freed_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void freed_request(struct request_list *rl, bool sync, req_flags_t rq_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814221f0)
Location: block/blk-core.c:1090
Inline: False
Direct callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff814221f0-ffffffff8142224e: freed_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void freed_request(struct request_list *rl, bool sync, req_flags_t rq_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144d070)
Location: block/blk-core.c:1168
Inline: False
Direct callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff8144d070-ffffffff8144d0ce: freed_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void freed_request(struct request_list *rl, bool sync, req_flags_t rq_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814802e0)
Location: block/blk-core.c:1273
Inline: False
Direct callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff814802e0-ffffffff8148033b: freed_request (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param reordered. </b>
<code>rl, flags</code> ➡️ <code>rl, op, flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool sync</code>
</li>
<li>
<b>Param added. </b>
<code>req_flags_t rq_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
