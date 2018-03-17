# SpringMVC

1. Implement AbstractController in StudentController. create a mapping index.html for it and render index.jsp view from it which displays messages "Hello from index.gsp"
2. Now remove AbstractController and useMultiActionController for StudentController which contains 2 actions one action renders a jsp view and another action uses HttpServletResponse to show the output on the Web browser.
3. Use annotation in StudentController to define a default action index which renders a jsp page.
4. Create one more annotation based action hello inside the StudentController which and use @ResponseBody annotation from it to display Hello world.
5. Create one more action which sends Model HelloWorld to the jsp file.
6. Use @PathVariable annotation to access firstname and lastname in an action inside StudentController place both the parameters in different arguments and access them.
7. Now place both the arguments inside a Map and access the Map instead.(Hint : check the slide for @PathVariable action returnCountryAndState  shows how to do it with map)
8. Use @RequestParam annotation to access the firstname and lastname in formData action of StudentController.
9. Create a StudentCO and bind firstname and lastname with instance variable of StudentCO.
10. Use @ModelAttribute annotation to add Heading "Spring MVC Demo" in every model.
