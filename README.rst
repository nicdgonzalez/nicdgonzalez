.. code:: cpp

  namespace nicdgonzalez {

    class AboutMe {
      public:
        char name[17] = "Nicolas Gonzalez";

        const char * SayHello(void) const noexcept {
          return "Thanks for stopping by, hope you find my work interesting!";
        }
    };

  }  // namespace nicdgonzalez
