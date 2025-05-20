# Function: <code>klp_shadow_free_struct</code>

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
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8110b6b0)
Location: kernel/livepatch/shadow.c:246
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff8110b6b0-ffffffff8110b703: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81116ea0)
Location: kernel/livepatch/shadow.c:246
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff81116ea0-ffffffff81116ef3: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81121120)
Location: kernel/livepatch/shadow.c:234
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff81121120-ffffffff81121178: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8112d740)
Location: kernel/livepatch/shadow.c:234
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff8112d740-ffffffff8112d798: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8113bec0)
Location: kernel/livepatch/shadow.c:234
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff8113bec0-ffffffff8113bf1b: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811365d0)
Location: kernel/livepatch/shadow.c:234
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff811365d0-ffffffff8113662b: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811373c0)
Location: kernel/livepatch/shadow.c:234
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff811373c0-ffffffff8113741b: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8115a070)
Location: kernel/livepatch/shadow.c:234
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff8115a070-ffffffff8115a0cb: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811834f0)
Location: kernel/livepatch/shadow.c:234
Inline: True
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff811834f0-ffffffff81183559: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811be670)
Location: kernel/livepatch/shadow.c:234
Inline: True
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff811be670-ffffffff811be6d9: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811d10a0)
Location: kernel/livepatch/shadow.c:234
Inline: True
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff811d10a0-ffffffff811d1107: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811e5d20)
Location: kernel/livepatch/shadow.c:234
Inline: True
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff811e5d20-ffffffff811e5d87: klp_shadow_free_struct (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (c0000000001f2340)
Location: kernel/livepatch/shadow.c:234
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
c0000000001f2340-c0000000001f23dc: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81125d20)
Location: kernel/livepatch/shadow.c:234
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff81125d20-ffffffff81125d78: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81118780)
Location: kernel/livepatch/shadow.c:234
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff81118780-ffffffff811187d8: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81123c10)
Location: kernel/livepatch/shadow.c:234
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff81123c10-ffffffff81123c68: klp_shadow_free_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klp_shadow_free_struct(struct klp_shadow *shadow, klp_shadow_dtor_t dtor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81130250)
Location: kernel/livepatch/shadow.c:234
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
**Symbols:**

```
ffffffff81130250-ffffffff811302a8: klp_shadow_free_struct (STB_LOCAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
