# Dieter Rams' [principles of good design](https://ifworlddesignguide.com/design-specials/dieter-rams-10-principles-for-good-design) applied to software engineering

## 1. Good software is innovative

Rebuild software using new technology. Build new software using stable technology.

## 2. Good software is useful

Always keep in mind that your application must bring some value to your users and make their life better.

## 3. Good software is aesthetic

Take a moment, step back, and look at your code: does it look beautiful?

We enjoy beauty because it embodies useful properties. Code that pleases the eye is often readable, idiomatic, and expressive. These are all qualities we value as programmers.

## 4. Good software is understandable

Beware of "clever" code if no-one can understand it. Well designed code should be straightforward and easy to comprehend, to others and your future self, and should be written for people, not for machines.

## 5. Good software is honest

Avoid abstractions you don't really need. Avoid cargo cult programming; strive to really understand everything that you write. Expose all the metrics you can extract from analyising your application, even the ones you might be unconfortable with, such as test coverage and antipatterns. Let them break the build so you can find time or help to fix them.

## 6. Good software is unobtrusive

Remove any obstacle between your users and the value your application can provide to them.

A well designed application is the fruit of many failed iterations that have been proofed by real users. Be sure to observe your users as they interact with your application. Take note of any friction and frustations. Treat their feedback as the most precious information you have and act on it.

## 7. Good software is long-lasting



## 8. Good software is thorough down to the last detail

Think deeply about every action your application performs. Gracefully handle every error condition you can imagine, e.g. memory and storage exhaustion, concurrent instances, network errors, lack of permissions, etc.

Create an sandbox environment where you become the user. Be strict and demanding with your application, as you generally are in that role. Have a map that describes every pathway inside your application, and make sure your standards of quality are always upheld in every situation.

## 9. Good software is environmentally friendly

Avoid wasting computational power or storage space. Consider the energy profile of your application. If your application isn't performing useful work, it should be inert.

## 10. Good software is as little software as possible

Less code is always better. Be terse, but expressive. Comments should be exceptional. 

Resist the urge to over-engineer. Once your application is "barely good enough", it is complete. Completeness derives from (1) absence of defects, (2) conformance to the agreed requirements, (3) fitness for purpose. You need all three, but nothing more.
