# jovsa notes

## Terms
 - Public Belief State (PBS)
 - World state
    - $w ∈ W$
 - Action
    - $A = A1 × A2 × ... x A_{N}$
 - Actions in Worlds
    - $Ai(w) denotes the legal actions for agent i at w and a = (a1, a2, ..., aN ) ∈ A$
 - Transition $T$
    - $T(w, a) ∈ ∆W$
 - Reward
    - $R_{i}(w, a)$
 - Private observation
    - $O_{priv(i)}(w, a, w')$
 - Public observation
    - $O_{pub}(w, a, w')$
 - History
     - $h = (w^0, a^0, w^1, a^1, ..., w^t)$
 - Infostate (action-observation history (AOH)) for a perticular agent
    -  $s_{i} = (O_{i}^0, a_{i}^0, O_{i}^1, a_{i}^1, ..., O_{i}^t)$; where $O_{i}^t$ = (Private observations + Public observations) of agent $i$ at time $t$
 - Public state
    -  $s_{pub} = (O^0_{pub}, O^1_{pub}, ..., O^t_{pub})$ for all public observations
 - Policy
   - By agent
 - Policy Profile or Expected Value (EV)
 - Nash Equilibrium
