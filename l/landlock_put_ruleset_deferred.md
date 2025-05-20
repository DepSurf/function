# Function: <code>landlock_put_ruleset_deferred</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void landlock_put_ruleset_deferred(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff815381b0)
Location: security/landlock/ruleset.c:383
Inline: False
Direct callers:
  - security/landlock/cred.c:hook_cred_free
```
**Symbols:**

```
ffffffff815381b0-ffffffff81538220: landlock_put_ruleset_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void landlock_put_ruleset_deferred(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81596870)
Location: security/landlock/ruleset.c:383
Inline: False
Direct callers:
  - security/landlock/cred.c:hook_cred_free
```
**Symbols:**

```
ffffffff81596870-ffffffff815968e0: landlock_put_ruleset_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void landlock_put_ruleset_deferred(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff81638d50)
Location: security/landlock/ruleset.c:385
Inline: False
Direct callers:
  - security/landlock/cred.c:hook_cred_free
```
**Symbols:**

```
ffffffff81638d50-ffffffff81638df0: landlock_put_ruleset_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void landlock_put_ruleset_deferred(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff816f0260)
Location: security/landlock/ruleset.c:385
Inline: False
Direct callers:
  - security/landlock/cred.c:hook_cred_free
```
**Symbols:**

```
ffffffff816f0260-ffffffff816f0300: landlock_put_ruleset_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void landlock_put_ruleset_deferred(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8172a600)
Location: security/landlock/ruleset.c:385
Inline: False
Direct callers:
  - security/landlock/cred.c:hook_cred_free
```
**Symbols:**

```
ffffffff8172a600-ffffffff8172a6a0: landlock_put_ruleset_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void landlock_put_ruleset_deferred(const struct landlock_ruleset * ruleset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ruleset.c (ffffffff8176bcb0)
Location: security/landlock/ruleset.c:520
Inline: False
Direct callers:
  - security/landlock/cred.c:hook_cred_free
```
**Symbols:**

```
ffffffff8176bcb0-ffffffff8176bd50: landlock_put_ruleset_deferred (STB_GLOBAL)
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
