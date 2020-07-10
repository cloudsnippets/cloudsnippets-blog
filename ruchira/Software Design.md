# Software Design

Design is an interesting subject.  We don’t usually think of design as a technical subject.  Design is more artistic and intuitive than rational or correct.  But design in engineering and technical fields combines all of these aspects.

I am going to suggest that ***software design is the combination of decomposition and integration***.

There are two ways a new product idea comes to you for design.  The first is when someone else gets an idea they think is brilliant or useful and is serious enough about the idea to ask you to build it.  The second is when you get your own product idea.  Let’s call this person who comes up with the idea the ***originator***.

Then comes the challenge.  You need to be very clear about what the idea means in terms of delivered functionality.  You find out that even when it is your own idea, you really have to get analytical about the idea to figure out what exactly it is that you want built.  Let’s launch into software development to get the idea into fruition.

## The Software Development Process

In the good old twentieth century, someone split the software development process based on task specialization.  This was a ***decomposition*** of the ***Software Development Life Cycle (SDLC)***.

People then blindly followed the model because the people who pushed the idea sounded serious and had the aura of knowing what they did.

> Here are those aspects:

> * Requirements Gathering (What they think they want)
> * Requirements Analysis (What we think they want)
> * Product Design (What we think will make them happy)
> * Product Development (How we make it for them)
> * Product Verification (Does it actually do what we want)
> * Product Maintenance (Keep adding features and fixes)

The components are still the same today.  The flow, however, has nothing to do with water.  We are now agile in terms of flow.

## Requirements Gathering

We have to talk to the originator to figure out the concept.  In requirements gathering, people break the problem down at a very high-level and these people also think that the hard part has been done by them and the rest is straight-forward.

But they break it down from their own point of view.  This is problem ***decomposition***.  Then they show how the parts they identified work together to deliver the complete solution.  This is ***integration*** of the parts and their functionality.  Already, we have decomposition and integration in the mind of the originator.

## Requirements Analysis

Now the professionals take a deep look at what is asked for.  You — ***domain experts*** — break the problem down into even smaller pieces in an attempt to understand exactly what the originator meant. However, during and after the analysis, you need to consult with the originator.

You break the problem down in some way (***decomposition***) and you figure out how the parts fit together (***integration***).  Then you run it by the originator.  If he does not fully agree, you do it again with the new information you learned. Rinse and repeat.

## Product Design

Now that you understand the problem, the solution is not merely one.  There can be multiple designs and multiple solutions.  This is a task for ***creative people*** with technical knowledge.

You discover a few high-level designs.  You break down the design into functional parts (***decomposition***).  You sort out how the parts work together (***integration***).  You evaluate your options for what you think is the best solution.  Then you meet the originator to convince him that this is actually the best solution.  Sometimes you give him multiple options.

## Product Development

Product development today is agile.  The ***originator understands the requirement holistically***, but not completely.  The ***architect understands the product design holistically***, but not completely.  This holistic points of view guide the process.

However, we do not hit the developers with all the information up front.  This is for two reasons.  One, we don’t know all the information about the requirements.  Two, we don’t know all the information about the solution.

Development is a dance between clarifying the requirements and  evolving the design.  We break the requirements and pick one at a time (***decomposition***).  We implement the requirement we picked, adding it into the system (***integration***).  Then we see how the whole thing works together.  Then we check with the originator.  Rinse and repeat.

## Product Verification

Product verification has a dual nature.  One, whether the developed features have been implemented accurately (***testing***).  Two, whether the product solves the problem satisfactorily and is there a better way of doing it (***validation***).

Testing is a process of defining multiple tests and test suites (***decomposition***) and making sure it works holistically (***integration***).  Validation is evaluating multiple options and picking the right one.

## Product Maintenance

In the good old waterfall days, a bunch of ***slick programmers*** implemented the product and once the originator accepted it, they handed it over to the ***grunt programmers*** for maintenance.  The assumption was that they had sorted the whole requirement and implemented it.  The grunts merely fixed bugs and made minor changes.

Today, we have ***product teams*** that are responsible from initiation to perpetual evolution of the product.  There is no marker for done.  Requirements are evolving and the design is not fixed.  The soundness of the design is tested almost everyday when you try to evolve the product.  The original requirements are a mere speck of dust in memory.

## Conclusion

Software development is ***art and science***.  It is also ***decomposition and integration***.  It is a ***dance***.  You need to be ***agile and nimble***.  It is ***a journey of design and evolution***.

The product and the process are evolved together.  The ***design of the product*** and the ***design of the process*** collectively evolve the software development industry. 
