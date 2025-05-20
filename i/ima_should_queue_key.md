# Function: <code>ima_should_queue_key</code>

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
bool ima_should_queue_key();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff8151ce80)
Location: security/integrity/ima/ima_queue_keys.c:166
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff8151ce80-ffffffff8151ce8b: ima_should_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ima_should_queue_key();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff81539d20)
Location: security/integrity/ima/ima_queue_keys.c:171
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81539d20-ffffffff81539d2b: ima_should_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ima_should_queue_key();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (ffffffff815423d0)
Location: security/integrity/ima/ima_queue_keys.c:174
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff815423d0-ffffffff815423db: ima_should_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ima_should_queue_key();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (0)
Location: security/integrity/ima/ima_queue_keys.c:174
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81cd74a4-ffffffff81cd74c7: ima_should_queue_key.cold (STB_LOCAL)
ffffffff815a23a0-ffffffff815a23b6: ima_should_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ima_should_queue_key();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (0)
Location: security/integrity/ima/ima_queue_keys.c:174
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81e8a6da-ffffffff81e8a707: ima_should_queue_key.cold (STB_LOCAL)
ffffffff81648800-ffffffff81648820: ima_should_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool ima_should_queue_key();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (0)
Location: security/integrity/ima/ima_queue_keys.c:174
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff820755fb-ffffffff82075628: ima_should_queue_key.cold (STB_LOCAL)
ffffffff81701530-ffffffff81701550: ima_should_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool ima_should_queue_key();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (0)
Location: security/integrity/ima/ima_queue_keys.c:174
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff820f515d-ffffffff820f518a: ima_should_queue_key.cold (STB_LOCAL)
ffffffff8173b5d0-ffffffff8173b5f0: ima_should_queue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool ima_should_queue_key();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue_keys.c (0)
Location: security/integrity/ima/ima_queue_keys.c:174
Inline: False
Direct callers:
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff821d2307-ffffffff821d2334: ima_should_queue_key.cold (STB_LOCAL)
ffffffff8177c190-ffffffff8177c1b0: ima_should_queue_key (STB_GLOBAL)
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
