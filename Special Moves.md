A special move is composed of three parts: a trigger, an effect, and the cost

The trigger dictates when you get to use the move, the effect is what happens during the move, and the cost is what it takes to use the move.

Each character has 10 times their level in special move points, which can be allocated to create special moves. If you want to change a part of a special move, you must spend 8 hours of training for each point added or subtracted.

The cost of a special move is calculated using the formula below:
Trigger points * effect points / cost points, rounded up in the case of fractions

A special move can have no more than 1 trigger condition, and 5 costs.

Triggers:
	Starting clauses:
		If... (2 points)
			Conditional for passive effects
		When... (2 points)
			Conditional for reactions and action improvements
		At will (15 points, if not used with a target, range, or condition, -4 points for each of used)
	Target clauses:
		Self (2 points)
		Ally (2 points)
		Enemy (3 points)
		Object (1 point for each value level)
	Range Clauses:
		Within X meters (3 points for 1 meter, extra 1 point per 2 meters afterwards)
		You can see (10 points)
		Adjacent (1 point)
		Within melee weapon reach (3 points)
		Self (0 points)
			Automatically selected if chose self for Target
	Condition clauses:
		Attacked (3 points)
		Makes an attack (3 points)
		Does a specific action other than attacking (2 points)
		Affected by a specific action other than attacking (2 points)
		Below X% hp (2 points at 10%, extra 1 point for every 5% above 10%)
		Requires specific status effect (3 points)
Effects:
	Intent:
		Damage/Healing (1 point)
		Manipulate position (1 point)
		Inflict status effects (1 point, +1 for each level of the effect)
		Specific action (1 point)
		Stat bonuses (2 points, +2 per stat increase)
	Range:
		Self (0 points)
		Adjacent (2 points)
		Cone (3 points per meter)
		Line (2 points per meter)
		Distance (1 point per 2 meters, must choose single target clause)
		Sphere (4 points per meter)
		Cube (4 points per meter)
		Sight (15 points, must choose the single target or the multiple targets options for your target clause)
		Weapon range:
			3 points if melee
			4 points if ranged
			If you choose weapon range, you must choose either the single target or the multiple targets options for your Target clause, and Self for the origin of this range
		If applicable:
			Origin:
				Self: 0 points
				Target within X meters:
					Ally: 1 point per 2 meters
					Enemy: 1 point per meter
					Anywhere: 3 points per 2 meters
					Anywhere including obstacles and barriers: 3 points per meter
	Targets:
		Single target (0 points)
		Multiple targets (2 points per extra target)
		First X targetable creatures (1 point per X, must have line or cone ranges)
		All targetable within range (3 times range cost, requires range)
		All allies within range (4 times range cost)
		All enemies within range (5 times range cost)
	Scale:
		Dice (1 point for each dice level, can have multiple dice)
		Number (1 point multiplied by the number's value divided by 2 rounded up)
		Duration (Varies)
			Conditional Duration (Same as trigger, but use Until or While as the starting clause. Divide the cost by 5 and round down)
			Time Duration (1 point for each turn)
			Concentration (3 points)
	Delivery:
		Certain (6 points)
		Attack roll (3 points)
		Stat contest (2 points)
		Saving throw (2 points)
		Mitigated Saving throw (1 point)
Costs:
	Base cost value: 1
	Requirement (Every move needs at least one of these):
		Action point (2 points per action point)
		Reaction point (2 points per reaction point)
		Requires you to preform action to happen (0 points)
	Resource:
		Loss of use of a certain Stat/Action for X turns (1 point per turn, 2 per turn if it is your highest stat at the time of this move's creation)
		Consumes a resource you have access to (2 points)
		Requires a certain object in your possession (1 point)
	Damage:
		Receive a status ailment (1 point per level, 1 point per turn of duration)
		Injure a part of your body (2^x points per level of severity)
		Take damage (1 point per dice tier)
		Reciprocal damage (1 point per severity)
	Use limits (must have one of both conditions):
		Charges:
			Stat (2 points, tied to a stat of your choice)
			Number (3/x points rounded normally, max 5)
		Recharge time
			Per Long Rest (6 points) 
			Per Short Rest (4 points)
			Per Combat (2 point)