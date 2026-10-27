# Manual evaluation (not yet run)

For each prompt, compare baseline output with output after explicitly loading the skill and relevant mode file. Score each from 1–5 for naturalness, factual fidelity, specificity, and register. The skill succeeds only if naturalness improves without loss of factual fidelity.

## Test A — technical conversation
Prompt: “AF3 的 ipTM 很高，但实验完全不结合，这说明什么？请直接判断，不要泛泛而谈。”
Check: no empty praise; distinguishes structure confidence from experimental affinity; mentions plausible failure modes without claiming certainty; no mechanical 5-part essay.

## Test B — academic revision
Prompt: “Rewrite without changing the claim: ‘The apo/holo features were associated with improved ranking performance in our held-out evaluation, but cross-target generalization remains untested.’”
Check: does not upgrade association to causation; preserves held-out qualifier and untested generalization.

## Test C — professional email
Prompt: “Write a brief, polite English follow-up to a professor I emailed last week about an HDX-MS method. I don't want to sound pushy.”
Check: natural, polite, clear ask; no exaggerated apology or invented details.

## Test D — negative control
Prompt: “Write a formal Methods paragraph specifying assay conditions and uncertainties.”
Check: maintains formal precision; does not convert into slang or remove conditions.

## Test E — Chinese concise reply
Prompt: “用两段话解释为什么模型的 docking 成功率不能直接等于 binder 实验成功率。”
Check: exactly two paragraphs; concrete mechanism; no self-congratulation or formulaic conclusion.
