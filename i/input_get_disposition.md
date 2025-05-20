# Function: <code>input_get_disposition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81669ac6)
Location: drivers/input/input.c:265
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816c9d72)
Location: drivers/input/input.c:263
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816f7d52)
Location: drivers/input/input.c:263
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8170d7d6)
Location: drivers/input/input.c:263
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8177ea16)
Location: drivers/input/input.c:263
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817bfa35)
Location: drivers/input/input.c:263
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817e6ee5)
Location: drivers/input/input.c:263
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81827925)
Location: drivers/input/input.c:259
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81858e85)
Location: drivers/input/input.c:261
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int input_get_disposition(struct input_dev *dev, unsigned int type, unsigned int code, int *pval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8192b4a0)
Location: drivers/input/input.c:261
Inline: False
Direct callers:
  - drivers/input/input.c:input_handle_event
```
**Symbols:**

```
ffffffff8192b4a0-ffffffff8192b76a: input_get_disposition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int input_get_disposition(struct input_dev *dev, unsigned int type, unsigned int code, int *pval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81932ba0)
Location: drivers/input/input.c:261
Inline: False
Direct callers:
  - drivers/input/input.c:input_handle_event
```
**Symbols:**

```
ffffffff81932ba0-ffffffff81932e6a: input_get_disposition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int input_get_disposition(struct input_dev *dev, unsigned int type, unsigned int code, int *pval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81915100)
Location: drivers/input/input.c:261
Inline: False
Direct callers:
  - drivers/input/input.c:input_handle_event
```
**Symbols:**

```
ffffffff81915100-ffffffff81915397: input_get_disposition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int input_get_disposition(struct input_dev *dev, unsigned int type, unsigned int code, int *pval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff819b7290)
Location: drivers/input/input.c:261
Inline: False
Direct callers:
  - drivers/input/input.c:input_handle_event
```
**Symbols:**

```
ffffffff819b7290-ffffffff819b7598: input_get_disposition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int input_get_disposition(struct input_dev *dev, unsigned int type, unsigned int code, int *pval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81b17100)
Location: drivers/input/input.c:272
Inline: False
Direct callers:
  - drivers/input/input.c:input_handle_event
```
**Symbols:**

```
ffffffff81b17100-ffffffff81b17428: input_get_disposition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int input_get_disposition(struct input_dev *dev, unsigned int type, unsigned int code, int *pval);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff81caa1f4)
Location: drivers/input/input.c:238
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/input.c:input_dev_freeze
  - drivers/input/input.c:input_dev_suspend
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:inhibited_store
```
**Symbols:**

```
ffffffff81ca8b80-ffffffff81ca8ee1: input_get_disposition (STB_LOCAL)
ffffffff820a6743-ffffffff820a6760: input_get_disposition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int input_get_disposition(struct input_dev *dev, unsigned int type, unsigned int code, int *pval);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff81d117c4)
Location: drivers/input/input.c:241
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/input.c:input_dev_freeze
  - drivers/input/input.c:input_dev_suspend
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:inhibited_store
```
**Symbols:**

```
ffffffff81d10090-ffffffff81d104c8: input_get_disposition (STB_LOCAL)
ffffffff82127b4a-ffffffff82127b6d: input_get_disposition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int input_get_disposition(struct input_dev *dev, unsigned int type, unsigned int code, int *pval);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff81dc73c4)
Location: drivers/input/input.c:241
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:__input_unregister_device
  - drivers/input/input.c:input_dev_freeze
  - drivers/input/input.c:input_dev_suspend
  - drivers/input/input.c:input_reset_device
  - drivers/input/input.c:inhibited_store
```
**Symbols:**

```
ffffffff81dc5c90-ffffffff81dc60c8: input_get_disposition (STB_LOCAL)
ffffffff822094cb-ffffffff822094ee: input_get_disposition.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffff800010a97f1c)
Location: drivers/input/input.c:261
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c0b7ac90)
Location: drivers/input/input.c:261
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c000000000b788a8)
Location: drivers/input/input.c:261
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffe0006a9c54)
Location: drivers/input/input.c:261
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8180de95)
Location: drivers/input/input.c:261
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817d55e5)
Location: drivers/input/input.c:261
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8184d015)
Location: drivers/input/input.c:261
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff818681d5)
Location: drivers/input/input.c:261
Inline: True
Inline callers:
  - drivers/input/input.c:input_handle_event
```
</details>
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
