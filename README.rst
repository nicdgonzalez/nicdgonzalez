.. code:: cpp

  namespace nicdgonzalez {

    class AboutMe {
      public:
        char name_[17] = "Nicolas Gonzalez";

        const char * SayHello(void) const noexcept {
          return "Thanks for stopping by, hope you find my work interesting!";
        }
    };

  }  // namespace nicdgonzalez
