
  
        Person person = new Person(  firstName: "Ivan",
                                     middleName: "Hristov",
                                     lastName: "Kostadinov",
                                     email: "nbukostadinov@gmail.com");

        person.setCode(new Code("Java"));

        person.setCourse(new Course("SoftUni", level: "Fundamentals", status: "Completed"));
        person.setCourse(new Course("SoftUni", level: "Java Advance", status: "In progress..."));
        person.setCourse(new Course("SoftUni", level: "JS Front End", status: "About to start"));

        person.setHobbies(new Hobby("Fishing"));
        person.setHobbies(new Hobby("PC Games"));
        person.setHobbies(new Hobby("Cinema"));

        person.setGoal(new Goal("I aspire to join an IT company where, I can contribute to substantial projects,
        immerse myself in challenging tasks, and gain a profound understanding of programming principles to enhance my skills."));

   

